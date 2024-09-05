# Kernel Compilation
## Using GitHub Actions to Compile Your Kernel Source Code

## Notice: This workflow is only applicable for compiling kernel sources hosted on GitHub

To speed up code fetching, the workflow uses `checkout` to pull the code instead of `git clone`

This means that only GitHub-hosted sources can be pulled, not external ones. A version with `git clone` for pulling will be released later for those who need it.

## Parameter Explanation

| Parameter Name | Parameter Description | Example |
| ------------ | -------------------- | ------------ |
| `AUTHOR` | Source code repository author | Veynamer |
| `CHECKOUT_REPO` | Repository to be pulled | android_kernel_xiaomi_mt6765 |
| `CHECKOUT_BRANCH` | Repository branch | alps-0.6 |
| `USEDEFCONFIG` | Defconfig used for compilation | certus_defconfig |
----------------------------------------------------------------------
