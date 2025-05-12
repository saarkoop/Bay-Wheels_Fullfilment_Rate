# Bay Wheels Dock Saturation Forecast

**Forecasting “full‑dock” events at Bay Wheels stations in San Francisco to optimize bike redistribution and improve rider experience.**

## Analysis Questions
- **Commuting vs. leisure:** Are full‑dock events driven primarily by rush‑hour commuters or by other trip purposes?  
- **Weather effects:** How do temperature and humidity influence saturation rates?  
- **Top predictors:** Which features (e.g., hour of day, rush‑hour flag, temperature band) most strongly drive our model’s forecasts?  
- **Operational trade‑offs:** What are the costs of issuing false alarms versus missing a true full‑dock event?

## Key Findings
- **Rush‑hour peaks dominate:** Morning and evening commuting windows account for the majority of saturation events.  
- **“Comfort zone” temperature band:** Dock usage climbs between 15–25 °C before leveling off.  
- **Minimal seasonality:** Monthly and seasonal indicators add little beyond time‑of‑day and weather signals.  
- **Prioritize recalls:** Missing a full‑dock event (false negative) harms rider trust more than an occasional false alarm.  
- **Model impact:** Our Gradient Boosted Machine yields a highly accurate, interpretable forecast that enables proactive repositioning and a smoother user experience.  
