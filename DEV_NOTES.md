# pxt-binbot-wit-2020

A MakeCode extensions for WITs Binbot Project

Originally developed by [robertsausg](https://github.com/robertsausg/pxt-binbot-wit).

## Development Notes

This can be used as a guide for how to use the repo and develop in your own separate branches to implement your assigned functionalities. This assumes that you're using the command line for development.

### 1.0. Starting the Development

1. Cloning the GitHub repo locally

```
git clone https://github.com/WIT-BinBot-2020/pxt-binbot-wit-2020.git
```

2. Ensure that you're in the `dev` branch via

```
git status
git checkout dev
```

3. Make your own branch to start developing your functionality

```
git checkout -b branchName
```

### 1.1. Finishing the Branch

When done your implementation for the branch, send the branch details and the functionality implemented to [andyAndyA](https://github.com/andyAndyA) to check for any potential merge conflicts.

Once the merge conflicts are resolved, the branch will be merged and you can move on to the next functionality to be implemented!

### 2.0. Continuing on Development

If you're upgrading or improving upon your merged feature that already has a branch, you can follow the steps below to update your branch to be ready for development;

1. Move back to your own branch to continue developing the functionality

```
git checkout branchName
```

2. Update your branch to be the same version as `dev`

```
git pull origin dev
```
