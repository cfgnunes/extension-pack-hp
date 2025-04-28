# Extension Pack HP

Extension Pack HP is a library developed in User RPL for HP 49 series calculators, including the HP 50g, HP 49g+, HP 49g, and HP 48GII. It brings features commonly found in other calculators, such as the HP 12c and modern Casio calculators, to the HP 49 series, helping to fill functional gaps left by the original firmware.

The library adds new features to the Finance, Time, and Statistics menus, including NPV, IRR, depreciation methods, probability distributions, and date operations. It also provides system tools, custom menus, and global commands for easier access and management.

![screenshot](screenshot.png)

## Features

### Numeric Solver Menu

Adds new applications to the Numeric Solver menu (keys: `Right Shift` → `7`) with:

- **Solve nonlinear system**

### Finance Menu

Adds new applications to the Finance menu (keys: `Left Shift` → `9`) with:

- **Net Present Value (NPV)**
- **Internal Rate of Return (IRR)**
- **Depreciation methods**
    - Straight-Line (SL)
    - Sum-of-the-Years Digits (SOYD)
    - Declining-Balance (DB)

### Time Menu

Adds new applications to the Time menu (keys: `Right Shift` → `9`) with:

- **Date add/subtract**
- **Date difference**

### Statistics Menu

Adds new applications to the Statistics menu (keys: `Right Shift` → `5`) with:
- **Probability Distributions**
    - Discrete: Binomial
    - Discrete: Poisson
    - Discrete: Bernoulli
    - Discrete: Uniform
    - Discrete: Neg. Binomial
    - Discrete: Geometric
    - Discrete: Hipergeometric
    - Continuous: Normal
    - Continuous: T-Student
    - Continuous: Chi² (Pearson)
    - Continuous: Exponential
    - Continuous: Uniform
    - Continuous: Gamma
    - Continuous: Beta
    - Continuous: Weibull
    - Continuous: Cauchy-Lorentz
    - Continuous: F-Distribution
    - Inverse: Binomial
    - Inverse: Poisson
    - Inverse: Normal
    - Inverse: T-Student
    - Inverse: Chi² (Pearson)
    - Inverse: Exponential
    - Inverse: Uniform (continuous)
    - Inverse: Weibull
    - Inverse: Cauchy-Lorentz
    - Inverse: F-Distribution

### APPS Menu

Adds new features under the APPS menu (key: `APPS`) with:

- **System tools**
    - Purge all HOME files
    - Reset system flags
    - Reset system flags for RPN mode
- **Custom menus**
    - Equations
    - Linear algebra
    - Combinatorics
    - Statistics
    - Finance

### Other commands

Adds new global commands, allowing access from anywhere in the calculator:

- `EXTPK` - Extension Pack HP Command Menu: Opens a centralized menu listing all features from the Extension Pack HP, providing a quick and convenient shortcut for easy access.
- `RESET` - Reset Command: Reset system flags and reinitializes the calculator for best use in RPN (Reverse Polish Notation) mode.
- `DSTAT` - Descriptive Statistics Command: Calculates all descriptive statistics (such as mean, standard deviation, median, and more) for a given array or list.
- `%TILE` - Percentile Command: Calculates the value corresponding to a specified percentile within an array or list.

## Contributing

If you spot a bug or want to improve the code or even improve the content, you can do the following:

- [Open an issue](https://github.com/cfgnunes/extension-pack-hp/issues/new)
  describing the bug or feature idea;
- Fork the project, make changes, and submit a pull request.
