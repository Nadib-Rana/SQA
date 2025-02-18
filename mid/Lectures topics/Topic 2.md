### **Testing vs Debugging **  

| Aspect           | **Testing (পরীক্ষা)** | **Debugging (ডিবাগিং)** |
|-----------------|--------------------|--------------------|
| **উদ্দেশ্য** | সফটওয়্যারে **বাগ (bug)** আছে কিনা পরীক্ষা করা With Locations | **বাগ চিহ্নিত ও সমাধান** করা |
| **কখন করা হয়?** | **Development ও Deployment** এর আগে | **Testing-এ বাগ ধরা পড়লে** করা হয় |
| **পদ্ধতি** | Unit Testing, Integration Testing, System Testing | Code analysis, print/debugging tools (e.g., Chrome DevTools, Debugger) |
| **কে করে?** | **QA টিম / টেস্টার** | **ডেভেলপার / প্রোগ্রামার** |
| **ফলাফল** | বাগ চিহ্নিত করে রিপোর্ট তৈরি করে | বাগ ফিক্স করে নতুন কোড লেখে |

🔹 **সংক্ষেপে:**  
- **Testing** → **বাগ খোঁজা** (Bug detection)  
- **Debugging** → **বাগ ঠিক করা** (Bug fixing)

- ### **Testing Goals Based on Test Process Maturity**  

✅ **Level 0 (Initial Stage):**  
- **Testing ও Debugging-এর মধ্যে পার্থক্য নেই।**  
- একে অপরের মতোই বিবেচিত হয়।  

✅ **Level 1 (Correctness Focused):**  
- **Testing-এর লক্ষ্য:** সফটওয়্যার **সঠিকভাবে কাজ করছে কিনা প্রমাণ করা।**  
- শুধুমাত্র কোডের সঠিকতা নিশ্চিত করা হয়।  

✅ **Level 2 (Failure Detection):**  
- **Testing-এর লক্ষ্য:** সফটওয়্যারে **ত্রুটি (bug) আছে কিনা তা খুঁজে বের করা।**  
- উদ্দেশ্য **ত্রুটি প্রমাণ করা, শুধুমাত্র সঠিকতা নয়।**  

✅ **Level 3 (Risk Reduction):**  
- **Testing-এর লক্ষ্য:** সফটওয়্যারের **ব্যবহারজনিত ঝুঁকি কমানো।**  
- সফটওয়্যার **ব্যবহারকারীর জন্য নিরাপদ কিনা তা নিশ্চিত করা।**  

✅ **Level 4 (Quality Improvement):**  
- **Testing হলো একটি মানসিক শৃঙ্খলা** যা **সফটওয়্যার ইঞ্জিনিয়ারদের উন্নত মানের সফটওয়্যার তৈরি করতে সহায়তা করে।**  
- **Development process-কে আরও সুসংগঠিত ও দক্ষ করে তোলে।**  

🔹 **সংক্ষেপে:**  
- **Level 0** → Testing & Debugging এক মনে করা হয়।  
- **Level 1** → Testing = **Correctness প্রমাণ করা।**  
- **Level 2** → Testing = **ত্রুটি (bug) খোঁজা।**  
- **Level 3** → Testing = **Risk কমানো।**  
- **Level 4** → Testing = **Quality উন্নত করা।**
