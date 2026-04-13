
---

# 📘 t-SNE Visualization Analysis Document

## 🔷 ১. Clear Cluster Separation (t-SNE-তে স্পষ্ট ক্লাস্টার)

![Image](https://images.openai.com/static-rsc-4/YMZ9ys_b2i89ZfxWub3AXkC-uw1W-6diRZNN24HYEovb1qA9IgOUlz2a8Ltf7eQv_lXlOLxwZcd4Kt5Nt6T7FwTfkh_8watlfHjmYx5UBonhArHYEy_IXXJikoaclc3rVvIp6crTOFVOaufdeHKO5WGm-DUAOVzGn8n2nJ_iMGWByTszyQSpTMWB7d_7fGT5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/vTLrk2k_PlFRECFlASnoaPuI55xKj3sMs6TzdZNDrcwRkamON5ZoOkgM7TfNMBIceAbHuCNAmmdp172Q5WYSWeWLFZqwkZiZkwATIdN16gTO3Etvt90JA9nrZ-VQAq2bwB3qG6mMWjuY0Zfi83QZwSBHyQESJ4nvALuvZ286mUgb58giXNGrc9HJna5s9AjH?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/iBCvnsyzfvyTD_7IZrzul3YZx2D_of8AeABhdrvVmEUJQZAkzrz708m6HuBuIuY2ZJ_v0o5NZsY57pcTotKUOXQGIDo4UjgIoew8MnXG_Xv5ncOKCCGPQHK6oaFQQSU5tJgyo71_4YBFL3GfcUv6KDhVqyW1xpBA47H2MUulwBWLuBsXxelyYouUgkeabKJ5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/qARcaVucjRW-PCRVCzLKkCFhbtyPqsZbqz06QJePpRgJ4DyajlIljd8ni9XaVvwVNjxOm_f4vURsqa13AXLXd71F0xN0cXwQM-3rgRTskapZB_Ha9rgY0uTYKbrKheuACXkQVaS0mThT3jor7tCgdRBCBKg_UiItx8bpQ3xgNeoU0GKPk4pjImFwzQx9gKez?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/kDZtooeq2r0BJfvKmAxNa8_yg6O6n_l2UWfsR6rKhc4GRzcsJlP009iwjVqHMkus5zw6OitRMX3kciMVOKmCEaHQK36u2vU3ZHUCK47IFbtQmFi9414qwuzNVTqT1DN5ioaejfuSusX4ll9AwYRPCSUkpJwjjn0iQ80LZfdjOJrf2iYLc8k5Cjdp--_1cmaV?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Zh65NF41l8X8FID7iLu5hVqfV9vC6DtZeOhUOCBq-OeoczM27P_p6dnE3DMX3SBI0oOd-YcLkS6oCU-5B3CCahQP8LBqMgdE_OfDqxiV014YwqO5uxrFJl97GoIrsP0vBsBCADjOOUgTDM80NnduFcndNYqKdC8bhsZmfGGzUZ78sqjBcHz5HwDAsNzertrz?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/t6rQKnl-5yEN-kasEMPCNNpWTdbWSUpQkPeLR84xKYlbwL0GgWfsgYul3guSXfxntGBkAc1v8tT3qjR66pBt2bTQZKE6YAdcLKAX7ij0jA-kaqb4smTBLkSulV0lgw8jogtoB9OmPoCv7A_lezLk0XqnnvYYsgFehd0XrHUVizaPSenD6L1ePR5Q5wckv4h1?purpose=fullsize)

### 📖 Explanation:

এই ধরনের t-SNE plot-এ দেখা যায়:

* প্রতিটি class আলাদা cluster তৈরি করেছে
* cluster গুলো খুব সুন্দরভাবে বিচ্ছিন্ন

👉 এর মানে:

* model feature ভালোভাবে শিখেছে
* local neighborhood structure ঠিক আছে

✔️ Interpretation:

* **High inter-class separability**
* classification সহজ

📌 t-SNE সাধারণত clustering খুব সুন্দরভাবে দেখায়

---

## 🔷 ২. Overlapping Clusters (মিশ্র ক্লাস্টার)

![Image](https://images.openai.com/static-rsc-4/gwVRwxn4Sdyr8yyl60xFqmHbguIQvChi4pbrOUr-EAozaX8kyAV_gRIPauIm7IefmIt5hTpUdAn1cou6ttHU1HmOuyzp7-QeM0hz5rHY5qb4JCMuHPnXjeN1SID32JbTgwfVSKu3nzV_bGK5OflAX1vCDtc8vfdXqX_TLhlbw_xNCHdOFX8OKpaXzDe5wWdG?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/iBCvnsyzfvyTD_7IZrzul3YZx2D_of8AeABhdrvVmEUJQZAkzrz708m6HuBuIuY2ZJ_v0o5NZsY57pcTotKUOXQGIDo4UjgIoew8MnXG_Xv5ncOKCCGPQHK6oaFQQSU5tJgyo71_4YBFL3GfcUv6KDhVqyW1xpBA47H2MUulwBWLuBsXxelyYouUgkeabKJ5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/77XuFlSbVZiteLscw_0lWd8uOhNU2KkR8DL9RI0ITBRhl25uzNQ8jNr9nPAG2AX0G2oEAmfSB90kyv3fdY9zuUI1hy-xr-YeeXq1N6mCxcadGwKAycxCTY_1qEGIiVTt2BeVuLCa1-pnv0dowciVlmUtCFrNYfMh810F0V6I3jSv2jswb6IzbmoVBBOdYXkM?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/4T4jNG8oNAPcwggjuL1gCDLxutQjgnGKEJmGp_6KgWk3V066VHMrk7TsGdEq30cCoyZROLnNj7X8z0nhyYm0ClCpxH_4Bi2GmXClzg2DFhgjfj5ReZLa-OQN6NDsULHbKrZyHmTyERsMVpQjCbQ4RN61BLKSkGHe2liRLxoDe_eU6kl4_3eOWtQEOSNmQpzj?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VrIkGiFjOog3KS4ov6HI6ThhswJiNjkYqw5w6AK_aeMn6fAymhUPyV6KZS3FHNAcz5wG_aoBncAMhZgDQWSCiiZRRE96axtNit3-urb33LmdmwPK5MGBX7CVMKyYO6wz3QBav7QUTxPji-qIvdRlSu9L0-biP3_mMlB83B5NCDxzUnVWCZzaV2wKfQLpbULz?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/loUB30VdGSxkrvxEa6yk5HpgRBJjAELDNV3QvoO1xN_QbTPkPxi_71XXjYmiv22NwAaHeUh5q_3BeyOjQ4AK7OVALlaVUzjxO9RS8nChIiQ3p_HXv6Cxz6obpXM0B6J1TT2mreFhOo5rTgI4_YycIyYf9fByb-_-sC_zxntFeFB2cb4UHXehq2iZTqAaLpi6?purpose=fullsize)

### 📖 Explanation:

এখানে:

* বিভিন্ন class overlap করছে
* boundary পরিষ্কার না

👉 এর মানে:

* feature representation দুর্বল
* model confuse

❌ Interpretation:

* **Low separability**
* fine-tuning দরকার

---

## 🔷 ৩. Tight & Compact Clusters (ঘন ক্লাস্টার)

![Image](https://images.openai.com/static-rsc-4/YMZ9ys_b2i89ZfxWub3AXkC-uw1W-6diRZNN24HYEovb1qA9IgOUlz2a8Ltf7eQv_lXlOLxwZcd4Kt5Nt6T7FwTfkh_8watlfHjmYx5UBonhArHYEy_IXXJikoaclc3rVvIp6crTOFVOaufdeHKO5WGm-DUAOVzGn8n2nJ_iMGWByTszyQSpTMWB7d_7fGT5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Zh65NF41l8X8FID7iLu5hVqfV9vC6DtZeOhUOCBq-OeoczM27P_p6dnE3DMX3SBI0oOd-YcLkS6oCU-5B3CCahQP8LBqMgdE_OfDqxiV014YwqO5uxrFJl97GoIrsP0vBsBCADjOOUgTDM80NnduFcndNYqKdC8bhsZmfGGzUZ78sqjBcHz5HwDAsNzertrz?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/iBCvnsyzfvyTD_7IZrzul3YZx2D_of8AeABhdrvVmEUJQZAkzrz708m6HuBuIuY2ZJ_v0o5NZsY57pcTotKUOXQGIDo4UjgIoew8MnXG_Xv5ncOKCCGPQHK6oaFQQSU5tJgyo71_4YBFL3GfcUv6KDhVqyW1xpBA47H2MUulwBWLuBsXxelyYouUgkeabKJ5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/ZODJYX7tWlK3m-cd7j9-NqpwkKVeo-UvbqsgDdRJJcIbJhOYUvLjWp-hQm8HSX0JF4Ie6qAiMz8X_jPpVh1D1alTjwrw5_soLI0l85WCp9kMbJJAWkoJbCIZXrgaJboTiJ9cw5r_xPkUo0esvVmXZ9Kqxluf4ZnlBQVTw8vTTBPbWa6Jxg49U1cpJc0ckVi3?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/OH9IX4IFHytNagxCCfI8Ac1L08oQx8TPjWBkjab1w66-8njL_OeLH3eMpwZREiwjvMxeij9ZMAceQtnT6AOW769c7g4Q0o6DAtIfWbTToVhTVu2J1A3bC6RhQrHB0OCchNjx3_58iox-PkXtunHuvL6natZicM72yjCG7DB3L_nW2Z0rNzFNqy7Ef5CQbEAh?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/po5fvRScLTQbN_ZfqLqeituZcnLTX2fY5P0Zx7FEsmh-I1e4ygRY6M7i-E9I69ZLp0XcMvUb7tSpXvIo1ntuqxk2J5hGKhbT0KOAUJWc1zIbxfc6Y8PQeZGrtye9M0AO_tAPwe3Coib_MRM_zb1wMuPiF24FVluY62T8iZWK-XPj09zn6ZtMTaMgXrAHvPhI?purpose=fullsize)

### 📖 Explanation:

এখানে:

* একই class-এর point খুব কাছাকাছি

👉 এর মানে:

* model একই class-এর feature consistentভাবে শিখেছে

✔️ Interpretation:

* **High intra-class compactness**
* reliable feature extraction

---

## 🔷 ৪. Fragmented Clusters (একই class ভেঙে যাওয়া)

![Image](https://images.openai.com/static-rsc-4/iBCvnsyzfvyTD_7IZrzul3YZx2D_of8AeABhdrvVmEUJQZAkzrz708m6HuBuIuY2ZJ_v0o5NZsY57pcTotKUOXQGIDo4UjgIoew8MnXG_Xv5ncOKCCGPQHK6oaFQQSU5tJgyo71_4YBFL3GfcUv6KDhVqyW1xpBA47H2MUulwBWLuBsXxelyYouUgkeabKJ5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/t6rQKnl-5yEN-kasEMPCNNpWTdbWSUpQkPeLR84xKYlbwL0GgWfsgYul3guSXfxntGBkAc1v8tT3qjR66pBt2bTQZKE6YAdcLKAX7ij0jA-kaqb4smTBLkSulV0lgw8jogtoB9OmPoCv7A_lezLk0XqnnvYYsgFehd0XrHUVizaPSenD6L1ePR5Q5wckv4h1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/vTLrk2k_PlFRECFlASnoaPuI55xKj3sMs6TzdZNDrcwRkamON5ZoOkgM7TfNMBIceAbHuCNAmmdp172Q5WYSWeWLFZqwkZiZkwATIdN16gTO3Etvt90JA9nrZ-VQAq2bwB3qG6mMWjuY0Zfi83QZwSBHyQESJ4nvALuvZ286mUgb58giXNGrc9HJna5s9AjH?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/OY3HW7SMT8ZlzGTkslUEb9Vhq7thFZySPjTax7CC6KeQ-Ex8-v5lkIfB-wwZAOwcteSJ90vsf2TAO6LGyzVOGun9P6uxAnMJFzjcWy5LR4i0qKcO0Opp26SmnsI6ttLl7M0-_ICgIj0T0FVCkRD50oUFnvwwR_IFlBQYZr0DZRweQAA7MQiAHZqgW2ToJZ-y?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/77XuFlSbVZiteLscw_0lWd8uOhNU2KkR8DL9RI0ITBRhl25uzNQ8jNr9nPAG2AX0G2oEAmfSB90kyv3fdY9zuUI1hy-xr-YeeXq1N6mCxcadGwKAycxCTY_1qEGIiVTt2BeVuLCa1-pnv0dowciVlmUtCFrNYfMh810F0V6I3jSv2jswb6IzbmoVBBOdYXkM?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/l9jZhkUWSIkj9LTZMNBvfOVWRKwuKgko9w_5rJNUBfiKSDY47OyAYH4Uirh7jj4lWGOK5AxCoackbUk-uU4ArKx3X7p8eOuf4OHwOZaE--OqUJrVJuMK_f27yTODQa8IYCdOiIZBdBZ4dtAZl--3sBUS9ME9xtfbVXAs0pi3Vjy0I5WsYN0MoKIpIvzDDmXt?purpose=fullsize)

### 📖 Explanation:

এখানে:

* একই class একাধিক ছোট cluster-এ ভাগ হয়ে গেছে

👉 এর মানে:

* class-এর মধ্যে variation বেশি
* model sub-pattern ধরছে

✔️ Interpretation:

* feature rich কিন্তু uneven
* data diversity বেশি

📌 t-SNE এই behaviour প্রায়ই দেখায়

---

## 🔷 ৫. Local Structure Preservation (t-SNE-এর বৈশিষ্ট্য)

![Image](https://images.openai.com/static-rsc-4/rDuPnnOz60Le-jtIbcl9X3AhkS6LVQl92OgIiTF0zDoqQ1ip_eoPJG175D0mfPQ4TM9-Ljl_Hs6jA4s3qTcFFoha_EXYc62rwupeyY-bWOekBOwLIijO0q2_kyj6FsSRyidZkgAySoC04dU-YnUPjjlv4UpuY2N0Vcc__Zh1wBXp3OBty7dnD6dcYFscgh_z?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Mltit3___ehGSZWyFyHEE8ex2XOeOPwnCSfNh5CpkdmiISA_TNkqoG5KNB5nFgtP4YY_3uLLfRCwSXwu07wQFeJfZ4esZkUkGFrRMhpkqeceB90YNHbcY124D4pR-orIYj9Qx2vEAEEJ72g8GOAcEco1E9-ijUysvcwe0ysFBxIIeucnz-0KdiKYwsNk09GL?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/HjF08lpdQv20To6nUQgVJvf56WuqgH9HES8uRYcQKh2kFrbjBfxTFry6hIy4IrLwd3dFdG8U96ZPADmJPFfD98dss8_X7pceP570r4NKrANYvlWKFJsAz51ogMMD-VeFvM7xFOW45gwZJjq-GYdtOJK_UpcQM5_Cpga8FnGLKypc8aYRi_wHaQK8ElHXtT7A?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/Kt-dGMPbJgX4n8_xY2lKzLjKoBYulkdoAviKLjs5MS4ELT3GNx06S7B4KOYtmw7GOwRejTWtzIGZtEJl2qOXHx085R-UMWPTwx6kRO5hShnYomP8zsoeqHakhjKaKoCLtHpfvUOsfSSla--Xzo5g_i5O0jnNURs_yV9X3g_h773oB1MyY30cZNJW6GeCnQa2?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/t6rQKnl-5yEN-kasEMPCNNpWTdbWSUpQkPeLR84xKYlbwL0GgWfsgYul3guSXfxntGBkAc1v8tT3qjR66pBt2bTQZKE6YAdcLKAX7ij0jA-kaqb4smTBLkSulV0lgw8jogtoB9OmPoCv7A_lezLk0XqnnvYYsgFehd0XrHUVizaPSenD6L1ePR5Q5wckv4h1?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/po5fvRScLTQbN_ZfqLqeituZcnLTX2fY5P0Zx7FEsmh-I1e4ygRY6M7i-E9I69ZLp0XcMvUb7tSpXvIo1ntuqxk2J5hGKhbT0KOAUJWc1zIbxfc6Y8PQeZGrtye9M0AO_tAPwe3Coib_MRM_zb1wMuPiF24FVluY62T8iZWK-XPj09zn6ZtMTaMgXrAHvPhI?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/2ymOc1T5aTJ5bkYexVDRB5RM10vQgRYJZbmaXdaQtAqbvO3S6jj_g_j6K4Aw5P9PB-crwRQyqv5ow4ua_tvfL0gHTmbBFwUpsaphfoP1kCURMXjlrvw7LVPv3G-mOmQokJZriaRZmcdXobAPewwohSNcDKdn70jZrkxZTPFhq8ZpnxPJ_iGMO6-69wSyIlg8?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/CRF321gQrXICuZMRxie5AwkxcL442UHUqjAE8Mqhd3Elsw0cnS2t0WvykYjyFwRreIqi8nxTTjBoZDK4VgNHEZKa2Ykcn0N0-dOgyLXgLDhP2naf45F_PSrkgtraeKGntfwK0f9HpChLgUMpmkGt6PGJ82WBpFRTZexXDcRsDddmgMiDy7mSYGrmm9WH3KD3?purpose=fullsize)

### 📖 Explanation:

👉 t-SNE-এর সবচেয়ে গুরুত্বপূর্ণ বৈশিষ্ট্য:

* কাছাকাছি point → সত্যিই similar
* কিন্তু দূরের cluster-এর distance → সবসময় meaningful না

✔️ Interpretation:

* **Local structure ভালো ধরে**
* **Global structure distort হতে পারে**

📌 তাই:

* cluster distance দিয়ে সিদ্ধান্ত নেওয়া ঠিক না

---

## 🔷 ৬. Before vs After Fine-tuning

![Image](https://images.openai.com/static-rsc-4/iBCvnsyzfvyTD_7IZrzul3YZx2D_of8AeABhdrvVmEUJQZAkzrz708m6HuBuIuY2ZJ_v0o5NZsY57pcTotKUOXQGIDo4UjgIoew8MnXG_Xv5ncOKCCGPQHK6oaFQQSU5tJgyo71_4YBFL3GfcUv6KDhVqyW1xpBA47H2MUulwBWLuBsXxelyYouUgkeabKJ5?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/0qqofkN8tndUvJM1G15Go_djtKp2Ch_HY-8MyqGAkFA57FVyCnCIV9wW9TfAKWOspfnmwONc7giy_afcZRDlaGr1ouY2Lo0-WI0AJAJzQZVAEFUZxlZG8oenqc1h0lIdifaH5DndYLX0e--DIjQoyjdepMyGYie58Jzsv-PK6zbeUx-NcrX8ioqqEUg_N8ao?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/AaHVWhxokNBn258Lnz2sn1ACAIJ9tykFCSSMrpS6ErGd-Wct3hGvlMY3_JIqkMXJuQK6BWRIEb_1MMRFFI5Zwj8lH1xP-QfeBAIQsndrgve2phrYWDBXVTNSDxS1OTp5OOcK-Gjss8Vp_YrvDGb6xPWiLIoNZbPTDsjBENAUNhArXui-tFRlxPPyWvu1UHfb?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/5Y8AsD2GWXtsmxDPKhiL0LBtJG0GqQGYj8GshA4ZqKoV4FAuVAoexnSkK2pkE6OuOIP2pzN2pvRqKvFkPrAZyDf3OgEOHMMIqN7kOJUP5zfriMkNCTCU7U2qeQrcWZD-Ozk41_wBIN0ssI_Jgrgda7H5Un2LpUo0zYU4rvp398tW32spPIUAMilFETY8LT3A?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/F4sMya3UQKjXnJVDP_HPAkOa3KUXNnclerxmriKJQvg-B_1d1_2JQi3WUNed4dnLhNXDtaRR_TcHRf_i9rbqstkQa5H2hAm7hpKemcOdXxmeAypCj8ecTEsIuCpenPMBpHoyW1nMdO-3u-l89Ywa-WNHQgz6LjcT_lsQkjkuhAAEOmULLslCKTdNnyw4S9yf?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/URmGl415m_c_rfUKqAqz5uTUWMMRHvKk0dxpVzrfTOZWuadyuMcAxG9m-QHUZYlvx0lJdN3MpNJmRcewN_cqhsaU_aDTrf9fXuYQGV9M-DVc1BS0dfZ-Kg-QGgOWKGlbnfK2OdlmtoD7xB-RLvMTqPHLTCj2f2dx7vzHwBHg44-c71PS1MXKTnZW7wYt3sT4?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/VQxeEKDeQ2hYv383fpKpuAJ_2NHkfVnXYAI3i7x8LLLG5MCuBeAflxvXoPrYceHrpxxJfOdQLUhpYZTsCcmB7YmzrsHa_ADiA41cyHXgCetmyTfv0oKPdPwpH0ggtOKFbpNzK_atnDE_bC_ZWEXDgXD2wb-gBv9TP0dG91Zyqi8zs2aTdfWualyNwhHhGtdw?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/vVca87d_Wd4kNRlB5SWzvCM3nW47zgwaAEMJqkoKBS0mSoubWOkpj7s2G9awqX4pOjZqwRx_6YldYKq_WqQndpRzUFFRdm2_MVTynr71HVhj_Q9bgwu6BwmU_mmkACeMGIYtjo6FcuUp6dQo6usN_OD2g267zQ6bYLmW6DBxWDDFa3pMvZqAN2HSHO369q-e?purpose=fullsize)

### 📖 Explanation:

### 🔹 Before Fine-tuning:

* cluster overlap
* unclear grouping

### 🔹 After Fine-tuning:

* clear cluster
* compact grouping

👉 এর মানে:

* fine-tuning feature representation উন্নত করে

✔️ Result:

* better clustering
* improved classification

---

# 🔷 🔚 Final Summary (t-SNE)

👉 t-SNE plot দেখে তুমি বুঝতে পারো:

* cluster tight কিনা → **feature quality**
* cluster আলাদা কিনা → **class separability**
* fragmentation আছে কিনা → **data variation**
* global distance misleading → **careful interpretation দরকার**

---

# 🔷 PCA vs t-SNE (Short Insight)

| Feature         | PCA    | t-SNE      |
| --------------- | ------ | ---------- |
| Type            | Linear | Non-linear |
| Structure       | Global | Local      |
| Cluster clarity | কম     | বেশি       |
| Interpretation  | সহজ    | tricky     |

---

✅ সবচেয়ে ভালো scenario:

* Tight + clear clusters
* fine-tuned model
* minimal overlap

---

