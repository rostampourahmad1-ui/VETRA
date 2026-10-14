# 🏗️ VETRA Platform Documentation

خوش آمدید! این مخزن شامل مستندات فنی، معماری سیستم، نیازمندی‌های محصول (SRS)، راهنماهای کاربری و مشخصات API پلتفرم **VETRA** است.

---

## 📑 فهرست مستندات (Documentation Index)

### 🏛️ معماری و مشخصات فنی (Architecture & System Design)
مستندات و تعاریف داده‌ای ساختار پلتفرم:
* [نقشه جامع سیستم (Global Map)](docs/architecture/VETRA_Global_Map.md)
* [گراف معماری سیستم (System Architecture Graph)](docs/architecture/VETRA_System_Architecture_Graph.json)
* [مدل داده اصلی (Core Data Model - MD)](docs/architecture/VETRA_Core_Data_Model.md) | [نسخه JSON](docs/architecture/VETRA_Core_Data_Model.json)
* [ماتریس دسترسی مبتنی بر نقش (RBAC Matrix - MD)](docs/architecture/VETRA_RBAC_Matrix.md) | [نسخه JSON](docs/architecture/VETRA_RBAC_Matrix.json)
* [ماشین وضعیت چرخه حیات (State Machine - MD)](docs/architecture/VETRA_Lifecycle_State_Machine.md) | [نسخه JSON](docs/architecture/VETRA_Lifecycle_State_Machine.json)

---

### 🔌 ارتباطات و وب‌سرویس‌ها (API Specifications)
قراردادها و تعاریف اینترفیس‌های نرم‌افزاری:
* [قراردادهای ارتباطی API (MD)](docs/api/VETRA_API_Contracts.md) | [نسخه JSON](docs/api/VETRA_API_Contracts.json)

---

### 📦 تعریف محصول و مشخصات ماژول‌ها (Product & Requirements)
* [سند نیازمندی‌های ماژول حقوق و دستمزد (HR Payroll SRS)](docs/product/HR_Payroll_Module_SRS.md)
* [درخت قابلیت‌های پلتفرم (Platform Feature Tree)](docs/product/VETRA_Platform_Feature_Tree.md)
* [راهنمای هویت بصری و برند (Brand Identity Guidelines)](docs/product/VETRA_Brand_Identity_Guidelines.md)
* [تعریف نقش‌های کاربری (User Roles)](docs/product/VETRA_User_Roles.md)

---

### 📖 راهنماهای کاربری و ماژول‌ها (User & Operations Manuals)
* [راهنمای داشبورد مدیریتی (Dashboard Documentation)](docs/user-guides/VETRA_Dashboard_Documentation.md)
* [چرخه مدیریت پروژه (Project Management Lifecycle)](docs/user-guides/VETRA_Project_Management_Lifecycle.md)
* [طراح خروجی و گزارش‌ساز (Output Designer Documentation)](docs/user-guides/VETRA_Output_Designer_Documentation.md)
* [راهنما و تحلیل برش میلگرد (RebarCut Study & User Manual)](docs/user-guides/VETRA_RebarCut_Study_and_User_Manual.md)

---

## 🛠️ مشارکت و به‌روزرسانی (Contribution)

1. قبل از ایجاد تغییر در تعاریف داده‌ای (`Core Data Model` یا `API Contracts`)، اطمینان حاصل کنید که هر دو نسخه `.md` و `.json` همگام‌سازی شده باشند.
2. برای اعمال تغییرات، یک شاخه (Branch) جدید ایجاد کرده و تغییرات خود را در قالب Pull Request ارسال نمایید.
`
