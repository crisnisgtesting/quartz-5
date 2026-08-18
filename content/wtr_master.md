---
cssclass: "wide-page"
type: wagon-type-master
source: "wtr_master"
---

# 🚂 Type Master

> [!abstract]+ 📋 Central Master Node
> This is the primary entry point for all ROAMS wagon types.
> Navigate through categories or jump to the **FMM Parameter Master** for inspection data.

---

## 📂 Wagon Class Groups

- [[Category_C]]
- [[Category_F]]
- [[Category_N]]
- [[Category_H]]
- [[Category_O]]
- [[Category_W]]
- [[Category_T]]
- [[Category_V]]
- [[Category_X]]


---

## 📊 Summary

> [!summary]
> - **Total Valid Wagon Types:** 149
> - **Total Categories:** 9

---

## 🔗 Related Centers

> [!tip]
> - [[fmm_params_master|FMM Parameter Master]] — Inspection & measurement parameters
> - [[wtr_master|ROAMS Wagon Master]] — This file

---

## 🗄️ Data Sources

> [!info]
> `wtr_master` ↔ `fmm_params`
>
> Relationship: `wtr_master.wagon_type = fmm_params.object_sub_type`
>
> Only records where `wtr_master.valid_flag = TRUE` are included.

