# Macro Zigzag Calculator

A simple static macro calculator for zigzag dieting.  
Set a calorie target, adjust macros, and choose one macro to auto-balance so the totals match your calorie goal.

## Features

- Adjustable sliders for:
  - Calories
  - Protein (g)
  - Fat (g)
  - Carbs (g)
- Auto-balance mode:
  - Auto-adjust **Carbs**, **Fat**, or **Protein** (you choose)
- Quick presets for an extreme zigzag schedule:
  - Low day: **1500 kcal**
  - High day: **2358 kcal**
- Real-time breakdown:
  - Calories from each macro
  - Total calories vs target
  - Difference and warnings when constraints prevent matching

## Macro math

- Protein: `4 kcal / g`
- Carbs: `4 kcal / g`
- Fat: `9 kcal / g`

Total calories:

`total = 4*protein + 9*fat + 4*carbs`

## How to run locally

1. Clone the repo
2. Open `index.html` in a browser (double click or drag into Chrome)
