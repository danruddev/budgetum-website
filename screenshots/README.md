# Screenshots

Place app screenshots here with the following naming convention:

```
{screen_name}_light.webp  - Light theme version
{screen_name}_dark.webp   - Dark theme version
```

## Required Screenshots

Based on the current Screenshots.tsx configuration:

| Screen Name | Light Version | Dark Version |
|-------------|---------------|--------------|
| budget | `budget_light.webp` | `budget_dark.webp` |
| analytics_breakdown | `analytics_breakdown_light.webp` | `analytics_breakdown_dark.webp` |
| analytics_trends | `analytics_trends_light.webp` | `analytics_trends_dark.webp` |
| transactions_list | `transactions_list_light.webp` | `transactions_list_dark.webp` |
| transactions_day | `transactions_day_light.webp` | `transactions_day_dark.webp` |
| accounts | `accounts_light.webp` | `accounts_dark.webp` |
| contacts | `contacts_light.webp` | `contacts_dark.webp` |
| input_calculator | `input_calculator_light.webp` | `input_calculator_dark.webp` |
| input_datepicker | `input_datepicker_light.webp` | `input_datepicker_dark.webp` |

## Recommended Dimensions

- Width: 320px (or 2x for retina: 640px)
- Height: ~693px to match phone aspect ratio (9:19.5)

## Compression Targets

- Preferred format: WebP (`.webp`)
- Target file size: ~60-180 KB per screenshot at 640x1386
- Keep visual quality high enough to preserve text readability
- Re-export screenshots when UI changes to avoid shipping stale pixels

The website will automatically display the correct version based on the user's theme preference.
