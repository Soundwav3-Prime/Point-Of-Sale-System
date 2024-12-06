# 🍹 Interactive Point-Of-Sale System

This repository contains a **Bash script** that provides an interactive terminal-based drink ordering system. Users can customize their orders by choosing from a variety of drinks, flavors, sizes, and add-ons, while the script calculates the total cost dynamically.

## Features

- **Drink Selection**: Choose from options like Shirley Temple, Lemonade, Iced Coffee, Frappe, Milkshake, and more.
- **Flavor Customization**: Pick specific flavors for certain drinks (e.g., Caramel Iced Coffee, Blood Orange Lemonade).
- **Size Options**: Regular or Large sizes, with price adjustments.
- **Add-Ins**: Include add-ins like Boba or additional flavors.
- **Dynamic Cost Calculation**: Total cost updates in real-time as you build your order.
- **Interactive Confirmation**: Confirm each selection and finalize your order when ready.

## Prerequisites

This script uses the **[gum](https://github.com/charmbracelet/gum)** utility to provide an interactive user experience. Ensure it is installed before running the script:

```bash
brew install gum # For macOS
