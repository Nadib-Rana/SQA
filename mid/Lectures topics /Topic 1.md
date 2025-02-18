### **Verification vs. Validation **  

- **✅ Verification (যাচাইকরণ)** → সফটওয়্যারটি **সঠিকভাবে** তৈরি হচ্ছে কি না তা নিশ্চিত করে।  
  - *প্রক্রিয়াভিত্তিক* (আমরা কি সঠিকভাবে বানাচ্ছি?)  
  - পদ্ধতি: **Code Review, Walkthrough, Inspection**  

- **✅ Validation (প্রমাণীকরণ)** → সফটওয়্যারটি **সঠিক কাজ করছে** কি না তা নিশ্চিত করে।  
  - *পণ্যভিত্তিক* (আমরা কি সঠিক জিনিস বানাচ্ছি?)  
  - পদ্ধতি: **Unit Testing, System Testing, UAT**  

**🔹 মূল পার্থক্য:**  
- **Verification** = *পরীক্ষার আগে* (Static)  
- **Validation** = *পরীক্ষার সময়/পরবর্তীতে* (Dynamic)
- ----------------------------------------------------------------------------------------
### **Verification vs. Validation Example**  

#### **✅ Verification (যাচাইকরণ) Example:**  
- **Scenario:** আপনি একটি **ই-কমার্স ওয়েবসাইট** তৈরি করছেন।  
- **Verification:**  
  - Requirement document, UI design **review** করা।  
  - Code **inspection** করে syntax errors বের করা।  
  - Database schema **design** চেক করা।  

#### **✅ Validation (প্রমাণীকরণ) Example:**  
- **Scenario:** সেই **ই-কমার্স ওয়েবসাইট** ব্যবহারকারী ঠিকভাবে ব্যবহার করতে পারছে কি না।  
- **Validation:**  
  - লগইন করার পর **ব্যবহারকারী পেজ লোড হচ্ছে কিনা** পরীক্ষা করা।  
  - **Order place** করার পর **সঠিক invoice পাচ্ছে কিনা** চেক করা।  
  - **Payment gateway কাজ করছে কিনা** টেস্ট করা।  


🔹 **সংক্ষেপে:**  
- **Verification** → "Code/design ঠিক আছে?" (পরীক্ষার আগের ধাপ)  
- **Validation** → "User ঠিকভাবে ব্যবহার করতে পারছে?" (পরীক্ষার পরের ধাপ)
- ![image](https://github.com/user-attachments/assets/c47ce44b-8b98-4179-93f8-abb75c7d708e)

