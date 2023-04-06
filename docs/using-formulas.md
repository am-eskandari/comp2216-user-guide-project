# Formatting Formulas

## Overview

Next, you will learn how to work with **[formulas in Microsoft Excel](https://support.microsoft.com/en-us/office/overview-of-formulas-in-excel-ecfdc708-9162-49e8-b993-c311f47ca173)**. Excel formulas helps you easily calculate, and manipulate data within your spreadsheets. Mastering Excel formulas can significantly improve your productivity and efficiency when working with data.

## Basic Formula Syntax

Excel formulas typically follow a specific syntax:

`=FUNCTION_NAME(arguments)`

- Formulas always begin with an equal sign (`=`).
- `FUNCTION_NAME` represents the name of the Excel function.
- `arguments` are the inputs or values required by the function, separated by commas.

For example, the formula `=SUM(6,8)` adds up the values `6` and `8`.

!!! note "Formatting Formulas with Cell References"

    Instead of using static numbers as we just showed, you can reference the cells the numbers are in instead. It makes your calculations modular, which means that it can be easily copied and pasted for other values on the table.

!!! warning "Caution"

    When using cell references in formulas, make sure you reference the correct cells. An incorrect reference can cause errors or produce incorrect results in your calculations.

    ![Incorrect Ref](./imgs/Using%20Formulas/incorrect-ref.png)

## Entering a Formula

To use a formula in your spreadsheet:

1. Click on the **cell** where you want to enter the formula.

    ![Click Cell](./imgs/Using%20Formulas/click-cell.png)

2. Type the **equal** sign (`=`) to *begin the formula*.

    ![Enter `=`](./imgs/Using%20Formulas/enter-equal.png)

3. Enter the **function name and its arguments**, either by typing them directly or by selecting the appropriate cells with your mouse.

    ![Enter `=`](./imgs/Using%20Formulas/enter-sum.png)

4. Press **Enter** to complete the formula.

    !!! success "Now you have entered your first Formula."

        ![Entering Formula](./imgs/Using%20Formulas/first-formula.png)

!!! information "Commonly used formulas"

    **SUM:** Adds up a range of cells or a list of values.

    **Formula Syntax:** `=SUM(number1, [number2], ...)`

    ![SUM](./imgs/Using%20Formulas/sum-example.png)

    **AVERAGE:** Calculates the average (arithmetic mean) of a range of cells or a list of values.

    **Formula Syntax:** `=AVERAGE(number1, [number2], ...)`

    ![AVERAGE](./imgs/Using%20Formulas/average-example.png)

    For more formulas, visit ***[the Official Documentation](https://support.microsoft.com/en-us/office/excel-functions-by-category-5f91f4e9-7b42-46d2-9bd1-63f26a86c0eb).***

## Copying and Filling Formulas

Excel allows you to copy and fill formulas across multiple cells, maintaining relative cell references automatically.

1. Click on the cell containing the formula you want to copy.

    ![Click cell](./imgs/Using%20Formulas/click-cell-to-copy.png)

2. Hover your mouse over the bottom-right corner of the cell until the cursor changes to a small black cross (the fill handle).

3. Click and drag the fill handle across the cells you want to fill with the formula.

    ![Click cell](./imgs/Using%20Formulas/click-drag.png)

4. Release the mouse button to complete the action. Excel will copy the formula to the selected cells, adjusting the cell references as needed.

    !!! success "Now you have copied and filled your first Formula."

        ![Click cell](./imgs/Using%20Formulas/first-fill.png)

    !!! warning "Caution"
        Be careful when copying and filling formulas with cell references. Ensure that the adjusted cell references in the copied formulas still refer to the correct cells and ranges to avoid errors or incorrect results. (It will give similar result to the previous referential error shown above.)


## Conclusion

Now that we completed this section, you are equipped with the following skills:

:material-check-circle:{ .green-checkmark }  The basic syntax of Excel formulas.

:material-check-circle:{ .green-checkmark }  How to enter a formula in a cell.

:material-check-circle:{ .green-checkmark }  Formatting formulas with cell references.

:material-check-circle:{ .green-checkmark }  Copying and filling formulas across multiple cells.

Great job 🤗. You can now effectively work with Excel formulas to perform calculations, manipulate data, within your spreadsheets.

>Click on the link below to move on to the next step: **[Creating a Chart](creating-charts.md)**
