# Week 2: Git Branching and GitHub

## Learning Objectives
- Create and manage branches
- Push code to GitHub
- Understand remote repositories
- Practice basic Git workflow

## Easy Tasks
1. **Create GitHub Repository**:
   - Click "New Repository" on GitHub
   - Name it "opensource-learning"
   - Make it public
   - Don't initialize with README (we'll push our own)

2. **Connect Local to GitHub**:
   ```bash
   cd my-first-repo
   git remote add origin https://github.com/yourusername/opensource-learning.git
   git branch -M main
   git push -u origin main
   ```

3. **Practice Branching**:
   ```bash
   git branch feature-1        # Create branch
   git checkout feature-1      # Switch to branch
   # Make some changes
   git add .
   git commit -m "Add feature 1"
   git push origin feature-1
   ```

4. **Merge Branch**:
   ```bash
   git checkout main
   git merge feature-1
   git push origin main
   ```

5. **Update Journal**: Document your Git workflow in journal.md

## Resources
- [Git Branching Tutorial](https://learngitbranching.js.org/)
- [GitHub Guides](https://guides.github.com/)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## LeetCode Problems (Easy)

### Problem 1: Roman to Integer
**LeetCode #13** | **Difficulty**: Easy

**Link**: https://leetcode.com/problems/roman-to-integer/

**Description**: Convert a Roman numeral to an integer.

**Example**:
```
Input: s = "III"
Output: 3
```

**Topics**: Hash Table, Math, String

---

### Problem 2: Valid Parentheses
**LeetCode #20** | **Difficulty**: Easy

**Link**: https://leetcode.com/problems/valid-parentheses/

**Description**: Determine if the input string has valid parentheses pairs.

**Example**:
```
Input: s = "()"
Output: true
```

**Topics**: String, Stack

## Submission
Update your `solutions.md`:
```markdown
# Week 2 Solutions

## Problem 1: Roman to Integer
**Solution Link**: [Your solution link]
**Status**: Accepted/Attempted
**Notes**: [Your notes]

## Problem 2: Valid Parentheses
**Solution Link**: [Your solution link]
**Status**: Accepted/Attempted
**Notes**: [Your notes]
```

## Next Week
We'll make our first open source contribution by creating a Pull Request!
