# 📊 INN Hotels Group Past Data - Data Dictionary

## 📌 Dataset Overview
- **Total Entries:** 27,093
- **Total Columns:** 12
- **Memory Usage:** ~2.5 MB

## 📂 Column Descriptions

| Column Name 🏷️                | Data Type 🔢📝 | Description 📝 |
|--------------------------------|--------------|---------------|
| `booking_id` 🆔               | Object       | Unique identifier for each booking. |
| `lead_time` ⏳                | Integer      | Number of days between booking date and arrival date. |
| `market_segment_type` 🎯      | Object       | Type of market segment (e.g., Online, Offline). |
| `no_of_special_requests` 🛎️  | Integer      | Number of special requests made by the customer. |
| `avg_price_per_room` 💰       | Float        | Average price per room per night in USD. |
| `no_of_adults` 👨‍👩‍👧‍👦         | Integer      | Number of adults staying in the booking. |
| `no_of_weekend_nights` 🌙     | Integer      | Number of weekend nights (Friday & Saturday) in the stay. |
| `arrival_date` 📅            | Object       | Date of arrival for the booking. |
| `required_car_parking_space` 🚗 | Integer  | Whether a parking space is required (1 = Yes, 0 = No). |
| `no_of_week_nights` 🌄        | Integer      | Number of weekday nights (Monday to Thursday) in the stay. |
| `booking_status` ✅❌         | Object       | Final booking status (Canceled or Not Canceled). |
| `rebooked` 🔄                | Object       | Whether the booking was rebooked (Yes/No). |

## 🔍 Observations:
- `rebooked` has **many missing values** (only 8,857 non-null values).
- `booking_status` is a **categorical variable** indicating cancellations.
- The dataset contains **both numerical and categorical variables**, useful for analysis.

🚀 **Next Steps:** You can use this dataset for **booking trend analysis, cancellation prediction, and revenue forecasting!**
