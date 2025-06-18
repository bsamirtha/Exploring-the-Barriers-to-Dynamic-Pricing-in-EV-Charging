# ⚡ EV Charging & Dynamic Pricing: A Data Science Case

The global EV market is set to hit **$1.5T by 2030**, with charging infra crossing **$200B**. Dynamic pricing — used in airlines and energy — could optimize EV charging revenue by adjusting prices based on demand or time.

💡 I explored this with a real dataset, aiming to build a dynamic pricing model.

> But the results were surprising — **EV users weren’t ready for dynamic pricing**, and neither was the infrastructure.

---

## 📂 Dataset Summary

- **Rows:** 1,320  
- **Source:** [Kaggle - EV Charging Patterns](https://www.kaggle.com/datasets/valakhorasani/electric-vehicle-charging-patterns)

Key columns include:

- `Energy Consumed`, `Charging Duration`, `Charging Cost`
- `Battery Size`, `SoC %`, `Distance Driven`
- `Time of Day`, `User Type`, `Charger Type`

---

## 📊 What I Found

- **Charging Cost is Stable** despite variation in energy/duration  
- **No strong correlation** between cost and any numeric or categorical feature  
- **No pattern = No pricing model** can be built

---

## 🤔 Final Insight

> It’s not just a data problem — it’s a market readiness issue.  
> Users prefer **simple, fixed pricing**, and current infrastructure doesn’t support real-time dynamic pricing.

---

### 🚀 Future Scope

Dynamic pricing in EVs is promising, but it needs:
- Smart infrastructure
- Policy backing
- User trust

Until then, **flat pricing** stays king.
