---

# 📘 UMAP Visualization Analysis Document

UMAP (Uniform Manifold Approximation and Projection)
---

## 🔷 ১. Clear Cluster Separation (স্পষ্ট ক্লাস্টার)

![Image](https://images.openai.com/static-rsc-4/rKZcREq7UQvCohNbM3APJpeOq10gpob8p29wjnqBPSY6dVx0tJC-zUJLjQxB67lOneWEX6jh2xpYlGGYhz7JbZ8lWkybbId55ezPsG3hJE-jgZ8oi8pC0ezx0gNdiPAIvK3e6hO7WGvfE6xf0bhSBQoD8xT7SpSR2cXnccBzmszHZrYkiVkQmPhXLQio5zM5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Sg7PpRg6cW26fSkNxthvt1x57ttngOmCiegt-Hp_h83gw4xcfoR2cIzzmm_TQmRfrWttajwJgvE3SIgyX76xVBZrT9_Rd8p9EvZWrjzgGBSfx7SX0qGS6N4XMJ8Uslc0ayVxHEKobnauR60kMY2TmkZw9A4xxoJ40LN_ynWyZp6IjN7Cu7uXSwzSqLWzif7h?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/grJ3Z3hYWbAIbzougIja_aLzkUhhqX5URCPZFSFtHVcGpVLgyfTewt0g4h4tl3La1oCafdPNN8J0XV9br_0YP48F_IQiYcvoKuLemEoFxS3HwlSPGKwYD6ylHJKQB1vVyApv5wlCRBr-IDiUSiyYlKtabVdMGkyKwnernKioQfeKMFIO713LnQBNSPTM_t5N?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/RZndD9zakbt4pZ6vA8g6CXH3_ClZCkYLD_cv7gjKTMtU1QUKm2j1lvo6bOEFAs_9yDqhasnoZft1RfF7HihbKLvepSKM9_C9eqSvW6z8r8_R5CFAwvh4TK5h5ELAp5I4TZkxgAzI8Dj7uinAqPxrR-fcOfoafqSPsOwviIdGHyAS8p9Vm_nK6rvm3Pq_l0DF?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/82DrcQWMzYNj-F387usddnBQmtqS3CJ9CRC1KM0BZ-eF6wUjPiZOOcrG-dRZmeGaY0hBH6VjmgceJPIeJ3i69gTV5jnnY_ZzUH1EwlI8dPLlfXSIAlH2sPB-xfkNYnLCFMyrEpAfMCn1la5gM5J6nYjejpq-uaWhp_yATpe8p2FDKm2zwt8Temh6-us2U-PK?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/UuHU6baWETFQYb9KhVkjzdYenojXb2_iKRENxt5ay4TsziHodQ09YbSzxg_hGqX0FOQqQFeKCFv0JNMn3NIMFwCwM9JZO9Nm3VVjjNI9MVRPLMAYa06u3qB6LjMLN9TZozNpReJqU44AsAjUIG9XmQtmD4XNtzOXEb1WhVLp4fxdH5BlRynEHlamjBrJ_Lta?purpose=fullsize)

### 📖 Explanation:

এই ধরনের UMAP plot-এ দেখা যায়:

* প্রতিটি class আলাদা cluster
* cluster গুলো পরিষ্কারভাবে বিচ্ছিন্ন

👉 এর মানে:

* model খুব ভালো feature শিখেছে
* class distinction স্পষ্ট

✔️ Interpretation:

* **High inter-class separability**
* classification performance ভালো

📌 UMAP সাধারণত PCA-এর থেকে better separation দেয়

---

## 🔷 ২. Overlapping Clusters (মিশে যাওয়া)

![Image](https://images.openai.com/static-rsc-4/Bo1-dY7kmn8e5tYhBxFRT5sR-PURvtizaUiVWAqQNq5YUVjh6z4u1BWwbXHsm-gK3AIUzEr8Pd5GSVikc1SgTuI4VQJpj2OkOngs0PkQD82DjHXplLaloOkurod9u4ysaBH1Zjs3qyczTaEU_d2L_TJAWtx-bax0dQcyAm405PWe3UgYx6pNMzQtzzFSKg4E?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/d8d4vShyZwM9SoQqF_1zm69822SUqkOW5MoodMx6ZmkxQWgkk450vkeXeaQ-nneBsrPI732wETug_rCI37hujiTMmHUycwAWicxGIx0HOm_bhu_xKM29slgboy7kMQQWyr1b9B1w9c0xvt9OLf7V8GWvomE9PvkY4RCENyBd9LpdRj1NMfGn0WPOYY-fA7Mo?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/ymjxJ7xiC2-9Sl3EWivo8RjsftkZkCQpjU7WaUKT7Kj56OFCpphKXqjDO2vYot2-mqjXVd4tzDVwCttHPd4iu2Tm-HOlyp0_-Wy0cW9V7jnwW-kZRBhW-QM4ByTC2rJYHT0ta6LwhNV40QytgsRUrXlXwZaBzC2xkGYI_5IGh7c1mfjA6Uo_63nFHRbG-kPb?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/rKZcREq7UQvCohNbM3APJpeOq10gpob8p29wjnqBPSY6dVx0tJC-zUJLjQxB67lOneWEX6jh2xpYlGGYhz7JbZ8lWkybbId55ezPsG3hJE-jgZ8oi8pC0ezx0gNdiPAIvK3e6hO7WGvfE6xf0bhSBQoD8xT7SpSR2cXnccBzmszHZrYkiVkQmPhXLQio5zM5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/dHjViOP4bcSVVBgWVjVmOh4Ne90yuEo2u46lXdlKq02385YH5m64vSglcMykZqbR4mD9MSLp9vgGuwsqlCNAtDGpKZUdYi7w5xVUGelnekUXWmf8WIBIFLCV5-RWpI64syEFAtgPal2eIX4F9r-kxLyzvoO2LQxMY5hXEALAe8UJ1ubPGKG1xGuar1OqvDmt?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/RZndD9zakbt4pZ6vA8g6CXH3_ClZCkYLD_cv7gjKTMtU1QUKm2j1lvo6bOEFAs_9yDqhasnoZft1RfF7HihbKLvepSKM9_C9eqSvW6z8r8_R5CFAwvh4TK5h5ELAp5I4TZkxgAzI8Dj7uinAqPxrR-fcOfoafqSPsOwviIdGHyAS8p9Vm_nK6rvm3Pq_l0DF?purpose=fullsize)

### 📖 Explanation:

এখানে:

* বিভিন্ন class overlap করছে
* boundary পরিষ্কার না

👉 এর মানে:

* model feature ঠিকমতো শিখেনি

❌ Interpretation:

* **Low separability**
* training বা data সমস্যা

---

## 🔷 ৩. Tight & Compact Clusters (ঘন ক্লাস্টার)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/FhQBsn-3_emlNbqnyHUYwmRHDYzWBuzH8CqiNXcr0_zCbPrF3GE_YUgedRvrLFPg_aqbapaULVwAVy6HP7bJytsVPNWnoXAeOINZdtjXtUNSMr5ygUJEtoLV3BFZefoNU9s8pXh4vG6bu6fPaR95_K4idcSgiW99jpj-_dFTvb59z6bHzYvXReFHcK6BS0d0?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/xkh5HRTliPVaBvSLTpYmwtCF4Pnrj9Gel_u6AWG9KU7rVIlIzEvYjwbgZesW8bsNFnAbI7fMOTBXEvqEbQ5FB33zC_J3k56tYHcMnz7SyXncxZqEwXx9ONgeSTEAXyZEzglSccS39ZMEwNvNiQlhtgKcMSHQaqlHUnuzbXsZ-FqRlYtFH5Ed6PJB3u6ybFzL?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/CdujdA_HKUlLn0lhRriaR4RgIAQBf34X3pCnmM2bqqagdUiSUM-y973EyWWfaqmcZuICehLcwCIiO8a36CeKAqOfpZxS-3a_xTbrWlLKjgOb9FTQAm6sVJ8t5hKzkEl9Ptt8XFKq33N5WrCPYl_k1IhoVQ9xygdI0QmNGLegysME4fBedmv8FK9qAZ8TP7fi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/BU-gKNaOf8oqYPtaG_xyvsCS_wS97YVMY3gyDcVAyBZaoUlJYm6XtUUCZ86hjXDWJmssAOjgZefkX8wm9vfkrWfGBj2JZvFNPAjmsJZUtTMY57KI2n8Dkk9RHzdztMGyvKon6wyRoyC_sDDZq9-mGqpgYriae8TGw7FqqBXfKTSLXK2qiV9ItehoGn-RMKT_?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/FtswM0VF34qlUi--PwGSNjs3svOju2Az0YMTb5M_sOIgAduZO2KlghP9meNRMWmXZIfdHHSk_I3VjYWqHK_U9pzkAkI8ykrpQgWxOv3wTO9biKXlMr0tt1xYIag3vsqdPxEkSvpuLh3x8xwdByizm061AVUMyfN1lweVNBox5czXC8UcQdIdzSSpa1RG5ZJh?purpose=fullsize)

### 📖 Explanation:

এখানে:

* একই class-এর point খুব কাছাকাছি

👉 এর মানে:

* model consistent feature শিখেছে

✔️ Interpretation:

* **High intra-class compactness**
* reliable representation

📌 ideal condition

---

## 🔷 ৪. Global + Local Structure Balance

![Image](https://images.openai.com/static-rsc-4/u_Ac7rlNYJkgaZ3Dxxk-m3Hd5DEaOVhQCiSnFPcUwn-IX2f1ny6IxKPmOGxM_alks3CHH6GM-275CVP-GYkmkVJboKn1tPQfzwCCJqk1oPEY2x26pD86qjbt3Ypkay9qSgGte9XIAIid0cQjZ8bKXDunBCEc4EKXJqQTz4MDGlxPgI209dL3Jp617vy0YR3O?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/NgMaMo3Hl6lpzW0S2l_zx8-E-FSDPnC0OlByLowT81xbaI1tqBbe3ipW1G5m0FI3zuh3vHtuLtIvPhV5myLv_ft-WkSJGmIjqrtJB86-NHh6yMPzcerPoqBoKwUD-2GJUZOo4vKyETWvAnVJS9LksCmoBA4IZolTy3Y09QJcC_wka9Y8yJGSbM118n162MDE?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/V2SS9cB36z-ML95jG-bmy4Ia7vKBijwKCEuOfIA004W9YBuJXRVLUUsOLkAUJs0dsI4rvlMmX8BTVroQv2JUqQLnuIxVAEKIFiFUW5W68-mlKtkmTvtCSVZHhVK4gUHHXgZ8Ho7tMOFoxwH4RbTd1y_d7imqphX8Mtf9zL4TdspQalFatKsKjp-ZJj8VenSJ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/fw44eTSY7OrMv7L8_wnVuOWtBP3nKZIJPvnDc2ahXzW5d6kFPxosOGx-ehzRuGFbI7Ccd6N_EJZVvB1kO68etL2m08lL15NAHC5490DfdKtm46hCuJR3Mco7YBAYTG5qmqTjQsyJ_blshKCdxzjDGD1NAxIRxNRWKMVkPGFRI2B2XxwtKnICzwsnjCgvCufj?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/CdujdA_HKUlLn0lhRriaR4RgIAQBf34X3pCnmM2bqqagdUiSUM-y973EyWWfaqmcZuICehLcwCIiO8a36CeKAqOfpZxS-3a_xTbrWlLKjgOb9FTQAm6sVJ8t5hKzkEl9Ptt8XFKq33N5WrCPYl_k1IhoVQ9xygdI0QmNGLegysME4fBedmv8FK9qAZ8TP7fi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/kTqDe1hCccb-vRvdoHWOvPUh5Zjdn7a8Aqc37GYm4rqZXKzaHXyr1Kkwd-Nf2sh2dmeWtoT_H9azKf78_E4lti4r-Ioauv96n3PEkcZczE7GD_vSkdGl1L_xq1dbjbaOZ7e4FqG7jbx-gZQCYeU6UwgDNWNcWj8Dtdk4b5HeDDgfg3Zhm_U6lgBrlny2YvSI?purpose=fullsize)

### 📖 Explanation:

👉 UMAP-এর বড় advantage:

* কাছের point → similar (local structure)
* cluster distance → কিছুটা meaningful (global structure)

✔️ Interpretation:

* PCA + t-SNE এর মাঝামাঝি behaviour
* structure বেশি realistic

---

## 🔷 ৫. Before vs After Fine-tuning

![Image](https://images.openai.com/static-rsc-4/mC3qeD0Z-NOkdC6fOf-YqCteONJ0ajJ8y1-8obsdVETiQVjeF0FcHyOLQeqh35pk0wslQEZEP8t-_fLczt1kegWEZL7Hmr_zAVMO4kFoJVBLQqKQbaSAyZrh7K7ThcF02IIh_ys4b_3F0C6xSZh9rqBJR97IEFtmAAURHNt7F6v26OKEA2hUM-_adgtxagFj?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/ly2jUllufZ-oy33eENwprztKvv4EJE2LBht5R9HsWVhhX8pKrjllDUvRGXIWXy0n9Fwz3vNzomV7AIh2KxeQveS--trUmM3dMKRsyxb3s6m4BPJXraLmPxhNBuUkW0zEPV-Foq45lftqd-6mdaRX85D8qK6r4zbUnHbn6kKEaY7uJxEucYa8dNvcveYkeZ2q?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/BdGom_JMpnAVyEjQpxmzSumfhz8mOvzjWXoEAt4SmTnFYpGcCMy9v1cxF84UkH-Yik8QXgvPGguRs2Ty9yOx5RtdUpxu-rzHQNbiotNdwHIbSXQpEzRMUhCTQ02Vna8Tg-H5MXjkuu0tdgpTZPJIAQXlheex-7wCtIC-RpP8sbcWuTB8TL4v2DBy2UuuObrg?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/9jz4LVh9F44kaiREPB-MKta_GZVnYjHfPvIFiSrxv2RwGqAfkdHOJiEdrx76e8GZofLzgcml46sUkSu7iTRswEC0Twl2LD1DD-SagtfjSXaC2_AeSzxzqJ4hYOSyMy4zfiwsrGVopnHI707cXUivwFHi1lNfsnhsATqDMUKuNGgLxMt074O1N_gz4e71AhTN?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Qxp0TtcWHAfUEl33Vhg4FjwjdjZouj5I9h0Cq1kYGf-mqoaNgOq-ODxzngUqg1-WLuxLljPGzfd9_iOfQPzFW24_Bn7zbDPfcDmRYaroLS10eoOcBRPsmIfZe6EZZBcAQUzxJJXOItfM7KWY_MHGaoBK0UKisrXG_MiH4kv4L2aU1o5nNStSMm9VwVZ4AE-c?purpose=fullsize)

### 📖 Explanation:

### 🔹 Before Fine-tuning:

* cluster mixed
* unclear separation

### 🔹 After Fine-tuning:

* clear cluster
* compact + separated

👉 এর মানে:

* fine-tuning feature quality উন্নত করে

✔️ Result:

* better clustering
* improved generalization

---

## 🔷 ৬. Realistic Cluster Shape (UMAP-এর বৈশিষ্ট্য)

![Image](https://images.openai.com/static-rsc-4/grJ3Z3hYWbAIbzougIja_aLzkUhhqX5URCPZFSFtHVcGpVLgyfTewt0g4h4tl3La1oCafdPNN8J0XV9br_0YP48F_IQiYcvoKuLemEoFxS3HwlSPGKwYD6ylHJKQB1vVyApv5wlCRBr-IDiUSiyYlKtabVdMGkyKwnernKioQfeKMFIO713LnQBNSPTM_t5N?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/WqxRzsyOdymvWy9_ZnFF8xEVAcdCJE_2Cng8f7sz-a8L_JqFt7M856nHwXrjvTmcet51O7S70PMnDGFZKZoTkElsmOJkJ29OrSQ3zFJZvakOd0Ntf-OB78Ctgret2uD33b4KiO6237Y44QabMSmjetDuJzt7YqVu4R2EVrV8k2ZrgU6mig0bDNAeVAXxCNjI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/CdujdA_HKUlLn0lhRriaR4RgIAQBf34X3pCnmM2bqqagdUiSUM-y973EyWWfaqmcZuICehLcwCIiO8a36CeKAqOfpZxS-3a_xTbrWlLKjgOb9FTQAm6sVJ8t5hKzkEl9Ptt8XFKq33N5WrCPYl_k1IhoVQ9xygdI0QmNGLegysME4fBedmv8FK9qAZ8TP7fi?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VAEEUqivUmC_4WeHTi29voGFXAdIHoE3nltx1QcYdaKQ-y_pqgEHZ2izOjynJ9_xPWXUW7lSzRnEH-cBVPWVBaZ_o89wIf0-JhkIJV5a5-OzRx6SYYXc5a2vtl7CgsOjKcJS3Mvenb12IpFCvCGbE7MHuWm_dw6YkuPC3sQN2BP6N-vSvkMj6vqrks-Q22X1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/anXZ76Cw3w6pWZeXQSd-Lw5J_ddn9UNqL5sNRLWJccPIwnJQKLO-pLA2pFWiDPJfM71OB2XsXL3qmlVIo8vX-O2Y3QhNHz6dNhkeZN_1V8oFz1nozWXZbJDe6dOqNANWtgUKHncNsKKt-mfrVhG227MVx0L-jrU1OLQqvMF__8IdyF6OjtRr73ycxyuDQ2eQ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/x2P8f_ysIe13vQ1GVGtD_pdLnbmmurRwcLBU8-p3qTISHG3e0CUWL_U_0g_WQ3--VmdG4KEYZs30RdU4ie2PcoWHCpADqEl-6L7BivnCTpkMtvmJ69SEZ0D3nRKRVxVXhTOUUfyaSUCHn0uOsXAZja2sb7kALqfRzuDna0sxyZ1fgwcUCnpxfif7-fdfN2NN?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/oNc-lcXrLv2q9ZCI7ETFuVIKgdEDtsJbjoZnoeni2euKxlve5qokVa6f7JsImRKLljdyPZeLok3au4JbqQdChci-_01kVTBReGXW2CuxGV_kWgOduB7om-EIy1nSJ9BsarIzmGYUZ_xgxfzpXfMjNL0UAPk3344R5wZmkdb-JNWmqD4Hd9dApvAQhjyIu_8w?purpose=fullsize)

### 📖 Explanation:

👉 UMAP-এ cluster সবসময় গোল হয় না:

* curved বা irregular shape হতে পারে

👉 এর মানে:

* data-এর underlying manifold structure ধরা পড়ছে

✔️ Interpretation:

* real-world data representation ভালো

---

# 🔷 🔚 Final Summary (UMAP)

👉 UMAP plot দেখে তুমি বুঝতে পারো:

* cluster separation → class distinction
* cluster tightness → feature quality
* shape → data structure
* distance → meaningful (t-SNE থেকে better)

---

# 🔷 PCA vs t-SNE vs UMAP (Final Comparison)

| Feature          | PCA    | t-SNE      | UMAP       |
| ---------------- | ------ | ---------- | ---------- |
| Type             | Linear | Non-linear | Non-linear |
| Structure        | Global | Local      | Both       |
| Cluster clarity  | Medium | High       | High       |
| Speed            | Fast   | Slow       | Fast       |
| Distance meaning | Good   | Poor       | Moderate   |

---

# ✅ Final Conclusion

👉 সবচেয়ে ভালো combination সাধারণত:

* Model: Fine-tuned CNN
* Method: **UMAP**

✔️ কারণ:

* clear cluster
* good separation
* realistic structure

---

