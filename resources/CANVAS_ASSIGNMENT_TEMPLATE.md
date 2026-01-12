# Canvas Assignment Template

Use this template for creating Canvas assignments for each week's lab.

---

## Week XX: [Lab Title]

**Lab repository folder**: [week##/](https://github.com/bgreenwell/is4010-course/tree/main/week##)

### Overview

This week's lab focuses on [brief topic description]. Complete the lab by following the detailed instructions in your forked repository.

### Instructions

1. **Navigate to the lab folder** in your forked repository:
   - Go to `week##/` in your repository
   - Read `README.md` for a quick overview
   - Read `lab##.md` for detailed instructions

2. **Complete the assignment**:
   - Write your code following the lab instructions
   - Test your solution locally (see testing instructions in `README.md`)
   - Commit and push your work to GitHub

3. **Verify your submission**:
   - Go to the **Actions** tab in your GitHub repository
   - Verify the "Week ## - [Topic]" workflow shows a **green checkmark** ✅
   - If you see a red ✗, click it to view the error and fix your code

### Submission

**No file upload required!** Your grade is automatically determined by your GitHub Actions CI/CD status.

Submit the **URL to your repository** on Canvas (one time only at the beginning of the semester).

### Grading

- ✅ **Green checkmark** in GitHub Actions = Full credit (10 points)
- ❌ **Red X** in GitHub Actions = No credit until fixed

**Due**: End of week (Sunday at 11:59 PM)

You may resubmit as many times as needed before the deadline. Only the final GitHub Actions status at the deadline counts.

### Getting Help

1. **Read the lab instructions thoroughly**: `week##/lab##.md`
2. **Check the troubleshooting guide**: [TROUBLESHOOTING.md](https://github.com/bgreenwell/is4010-course/blob/main/resources/TROUBLESHOOTING.md)
3. **Review test expectations**: Check the test file in `week##/tests/`
4. **Use AI assistance**: GitHub Copilot, Claude, ChatGPT (with understanding)
5. **Ask on Microsoft Teams**: Post your question in the course channel
6. **Attend office hours**: Get direct help from the instructor

### Academic Integrity

You are encouraged to use AI coding assistants (GitHub Copilot, Claude, ChatGPT, etc.) to help with this lab. However:
- You must **understand** all code you submit
- You must be able to **explain** how your code works
- The goal is **learning**, not just completion

### Resources

- **Lab instructions**: [week##/](https://github.com/bgreenwell/is4010-course/tree/main/week##)
- **Course repository**: [is4010-course](https://github.com/bgreenwell/is4010-course)
- **Setup guide**: [SETUP_GUIDE.md](https://github.com/bgreenwell/is4010-course/blob/main/resources/SETUP_GUIDE.md)
- **Textbook chapter**: Chapter ## - [Topic]

---

## Example Assignments

### Week 00: Setup Verification

**Lab repository folder**: [week00/](https://github.com/bgreenwell/is4010-course/tree/main/week00)

### Overview

This is a **test lab** to verify your development environment and GitHub Actions CI/CD are working correctly. This lab is **not graded** and contains no actual course content - it's purely for setup verification.

### Instructions

1. **Navigate to the lab folder** in your forked repository:
   - Go to `week00/` in your repository
   - Read `README.md` for a quick overview
   - Read `lab00.md` for simple instructions

2. **Complete the verification**:
   - Create `lab00.py` with two simple functions (instructions provided)
   - Run `pytest tests/ -v` to test locally
   - Commit and push your work to GitHub

3. **Verify your setup works**:
   - Go to the **Actions** tab in your GitHub repository
   - Verify the "Week 00 - Setup Verification" workflow shows a **green checkmark** ✅

### Submission

No submission required for Week 00 - this is just for your own verification.

### Purpose

Week 00 proves:
- ✅ Your Python environment works
- ✅ pytest is installed and functional
- ✅ GitHub Actions CI/CD works
- ✅ You understand the weekly workflow

Once Week 00 passes, you're ready for the actual course labs!

---

### Week 03: Python Basics and Testing

**Lab repository folder**: [week03/](https://github.com/bgreenwell/is4010-course/tree/main/week03)

### Overview

This week's lab focuses on Python fundamentals and automated testing with pytest. You'll write basic Python functions and verify them with unit tests, establishing the testing workflow you'll use for all future labs.

### Instructions

1. **Navigate to the lab folder** in your forked repository:
   - Go to `week03/` in your repository
   - Read `README.md` for a quick overview
   - Read `lab03.md` for detailed instructions

2. **Complete the assignment**:
   - Create `lab03.py` with required functions
   - Test files are provided in `tests/test_lab03.py`
   - Run `pytest tests/ -v` to test locally
   - Commit and push your work to GitHub

3. **Verify your submission**:
   - Go to the **Actions** tab in your GitHub repository
   - Verify the "Week 03 - Python Basics" workflow shows a **green checkmark** ✅

### Submission

Submit the **URL to your repository** on Canvas (if not already submitted).

### Grading

- ✅ **Green checkmark** in GitHub Actions = Full credit (10 points)
- ❌ **Red X** in GitHub Actions = No credit until fixed

**Due**: End of week (Sunday at 11:59 PM)

### Getting Help

1. **Read the lab instructions thoroughly**: [week03/lab03.md](https://github.com/bgreenwell/is4010-course/blob/main/week03/lab03.md)
2. **Work through the interactive notebook**: `week03/notebook.ipynb`
3. **Check the troubleshooting guide**: [TROUBLESHOOTING.md](https://github.com/bgreenwell/is4010-course/blob/main/resources/TROUBLESHOOTING.md)
4. **Review test expectations**: Check `week03/tests/test_lab03.py`
5. **Ask on Microsoft Teams**: Post your question in the course channel

---

### Week 09: Rust Basics

**Lab repository folder**: [week09/](https://github.com/bgreenwell/is4010-course/tree/main/week09)

### Overview

Welcome to Rust! This week introduces Rust fundamentals: installing the toolchain, creating Cargo projects, and writing basic Rust code with variables, functions, and tests.

### Instructions

1. **Navigate to the lab folder** in your forked repository:
   - Go to `week09/` in your repository
   - Read `README.md` for a quick overview
   - Read `lab09.md` for detailed instructions

2. **Complete the assignment**:
   - Edit `src/main.rs` with your Rust code
   - Run `cargo test` to test locally
   - Run `cargo clippy` to check code quality
   - Commit and push your work to GitHub

3. **Verify your submission**:
   - Go to the **Actions** tab in your GitHub repository
   - Verify the "Week 09 - Rust Basics" workflow shows a **green checkmark** ✅
   - This workflow checks: build, test, formatting, and clippy

### Submission

Submit the **URL to your repository** on Canvas (if not already submitted).

### Grading

- ✅ **Green checkmark** in GitHub Actions = Full credit (10 points)
- ❌ **Red X** in GitHub Actions = No credit until fixed

**Due**: End of week (Sunday at 11:59 PM)

**Note**: Rust workflows verify multiple checks:
- `cargo build` - Code compiles
- `cargo test` - Tests pass
- `cargo fmt --check` - Code is formatted correctly
- `cargo clippy` - No linter warnings

### Getting Help

1. **Read the lab instructions thoroughly**: [week09/lab09.md](https://github.com/bgreenwell/is4010-course/blob/main/week09/lab09.md)
2. **Read Rust compiler errors** - They're very helpful!
3. **Check The Rust Book**: [doc.rust-lang.org/book](https://doc.rust-lang.org/book/)
4. **Ask on Microsoft Teams**: Post your question in the course channel

---

## Quick Copy-Paste Templates

### Python Lab (Weeks 3-8)

```markdown
**Lab repository folder**: [weekXX/](https://github.com/bgreenwell/is4010-course/tree/main/weekXX)

Complete this week's lab by following the instructions in your forked repository.

**Instructions:**
1. Go to `weekXX/` in your forked repository
2. Read `README.md` and `labXX.md`
3. Create `labXX.py` with your solution
4. Run `pytest tests/ -v` to test locally
5. Commit and push to GitHub
6. Verify GitHub Actions shows green ✅

**Grading**: Green checkmark in GitHub Actions = 10 points

**Due**: End of week (Sunday at 11:59 PM)

**Help**: [labXX.md](https://github.com/bgreenwell/is4010-course/blob/main/weekXX/labXX.md) | [TROUBLESHOOTING.md](https://github.com/bgreenwell/is4010-course/blob/main/resources/TROUBLESHOOTING.md) | Microsoft Teams
```

### Rust Lab (Weeks 9-14)

```markdown
**Lab repository folder**: [weekXX/](https://github.com/bgreenwell/is4010-course/tree/main/weekXX)

Complete this week's Rust lab by following the instructions in your forked repository.

**Instructions:**
1. Go to `weekXX/` in your forked repository
2. Read `README.md` and `labXX.md`
3. Edit `src/main.rs` with your Rust code
4. Run `cargo test` and `cargo clippy` locally
5. Commit and push to GitHub
6. Verify GitHub Actions shows green ✅ (checks: build, test, fmt, clippy)

**Grading**: Green checkmark in GitHub Actions = 10 points

**Due**: End of week (Sunday at 11:59 PM)

**Help**: [labXX.md](https://github.com/bgreenwell/is4010-course/blob/main/weekXX/labXX.md) | [The Rust Book](https://doc.rust-lang.org/book/) | Microsoft Teams
```

---

## Canvas Assignment Settings

**Assignment Type**: Online submission
**Submission Type**: Website URL
**Points**: 10 (except Week 00: 0)
**Due Date**: Sunday at 11:59 PM
**Available From**: Monday of the week
**Until**: Sunday at 11:59 PM (allow late submissions with penalty if desired)

**Grading Type**: Points
**Group Assignment**: No
**Peer Reviews**: No
**Anonymous Grading**: No

---

## Notes for Instructor

- Students submit their repository URL **once** at the beginning of the semester
- All labs are graded by checking the GitHub Actions status
- Students can resubmit unlimited times before the deadline
- The final GitHub Actions status at the deadline determines the grade
- Green checkmark = full credit, Red X = no credit
- Consider allowing 24-48 hour grace period with small penalty for late fixes
