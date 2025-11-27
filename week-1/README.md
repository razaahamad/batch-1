# Week 1: Introduction to Open Source and Git Basics

## Learning Objectives
- Understand what open source software is
- Install and configure Git
- Learn basic Git commands
- Create your first GitHub account

## Easy Tasks
1. **Install Git**: Download and install Git from [git-scm.com](https://git-scm.com)
   ```bash
   git --version  # Verify installation
   ```

2. **Configure Git**:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
   ```

3. **Create GitHub Account**: Sign up at [github.com](https://github.com)

4. **First Local Repository**:
   - Create a folder named "my-first-repo"
   - Initialize Git: `git init`
   - Create a README.md file with your name
   - Add file: `git add README.md`
   - Commit: `git commit -m "My first commit"`

5. **Create Learning Journal**: Make a `journal.md` file to track weekly learnings

## Resources
- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Hello World](https://guides.github.com/activities/hello-world/)
- [What is Open Source?](https://opensource.com/resources/what-open-source)

## LeetCode Problems (Easy)

### Problem 1: Two Sum
**LeetCode #1** | **Difficulty**: Easy

**Link**: https://leetcode.com/problems/two-sum/

**Description**: Given an array of integers `nums` and an integer `target`, return indices of two numbers that add up to target.

**Example**:
```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
```

**Topics**: Array, Hash Table

---

### Problem 2: Palindrome Number
**LeetCode #9** | **Difficulty**: Easy

**Link**: https://leetcode.com/problems/palindrome-number/

**Description**: Determine whether an integer is a palindrome without converting it to a string.

**Example**:
```
Input: x = 121
Output: true
```

**Topics**: Math

## Submission Instructions
Create a `solutions.md` file in this week's folder with:
```markdown
# Week 1 Solutions

## Problem 1: Two Sum
**Solution Link**: [Your LeetCode solution URL or GitHub gist]
**Status**: Accepted/Attempted
**Notes**: [Any challenges or learnings]

## Problem 2: Palindrome Number
**Solution Link**: [Your LeetCode solution URL or GitHub gist]
**Status**: Accepted/Attempted
**Notes**: [Any challenges or learnings]
```

## Next Week
We'll learn Git branching and push our first code to GitHub!
