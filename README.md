# ๐ง ์ง๋ญ๋ฃ(์ง๊ธ ๋ญ ๋ฃ์ง?)
#### '์ง๋ญ๋ฃ'์ ์์น ๊ธฐ๋ฐ ์ฌ์ฉ์ ๊ฐ ์์ ์ถ์ฒ ์ดํ์๋๋ค. <br><br><br>

## ๐ค <I>Why?</I> :: ํ๋ก์ ํธ ๊ฐ์
> ๋งค์ผ ๋ค๋๋ ๊ณจ๋ชฉ ๊ธธ์ ๊ฑธ์ ๋๋ง๋ค ๋ฃ๋, ํด๊ทผ ๊ธธ์, ์ฌํ์ง์์... ์ฒ๋ผ ๋ชจ๋๋ค ์ฅ์์ ๊ด๋ จ๋ ์์์ด ํ ๊ณก์ฏค์ ์์ ๊ฒ ์๋๋ค.<br><br>
> <b><I>'์ง๋ญ๋ฃ'</I></b> ์ ์ ์ ๋ผ๋ฆฌ ๋จ์ํ ์์๋ง์ ์ถ์ฒํ๋ ๊ฒ์ ๋์ด,  
> ์์น์ ์์์ <b>"๊ฐ์ "</b>์ผ๋ก, ์ ์ ์ ์ ์ ๋ฅผ <b>"๊ณต๊ฐ"</b>์ผ๋ก ์ฐ๊ฒฐํ๊ธฐ ์ํด ๋ง๋ค์ด์ก์ต๋๋ค.

<br>

## ๐ <I>What?</I> :: ํ๋ฉด ๋ฐ ๊ธฐ๋ฅ<br>

> ### ์ฃผ์ ๊ธฐ๋ฅ
> * ์์น๋ฅผ ๊ธฐ๋ฐ์ผ๋ก ์์ ์ถ์ฒ<br>
> * ์์ ์ ๋ณด ํ์ธ ๋ฐ ์์ ๋ฃ๊ธฐ<br>
> * ์ถ์ฒ ์์ ๋ณ ๋๊ธ ๋ฐ ๊ณต๊ฐํ๊ธฐ<br>
> * ์ง์ญ ๋ณ ์ธ๊ธฐ ์ฐจํธ ์ ๊ณต<br>
> ### ํ๋ฉด ๋ฐ ๊ธฐ๋ฅ ์ค๋ช
> <details>
> <summary>1. ๋ฉ์ธ ํ๋ฉด</summary>
> <img src="https://user-images.githubusercontent.com/92194918/221408397-dd19e300-04d5-4979-80e2-f455bd79976e.gif" width="240"/><br>
> <ul> 
> <li><b>์ง๋ ์์ ์์ฑ๋ ์์ ํ์ ํตํด ๋ด ์์น ์ฃผ๋ณ์์ ์์ฑ๋ ์์ ์ ๋ณด๋ฅผ ํ์ธํ  ์ ์์ต๋๋ค.</b></li>
> <li>Splash์์ FusedLocation์ ํตํด ์ ์ ์ ํ์ฌ ์์น ์ ๋ณด๋ฅผ ๊ฐ์ ธ์ MainActivity๋ก ์ ๋ฌํฉ๋๋ค.</li>
> <li>MainActivity์์ ์ ๋ฌ๋ฐ์ ์์น ์ ๋ณด๋ฅผ ViewModel์ LiveData์ ์ ์ฅ ํ<br> ViewModel์ Observer๋ฅผ ํตํด LiveData๋ฅผ ๊ฐ์งํ์ฌ ํด๋น ์์น ์ ๋ณด๋ฅผ ๊ธฐ์ค์ผ๋ก ์ง๋ ํ๋ฉด์ ํ์ํฉ๋๋ค.</li>
> <li>LiveData์ ์ ์ฅ ๋ ์์น ์ ๋ณด๋ฅผ ๊ธฐ์ค์ผ๋ก ๋ฐ๊ฒฝ 5km ๋ด์ ์์ฑ ๋ ์์ ํ ๋ฐ์ดํฐ๋ฅผ Coroutine ํตํด ๋น๋๊ธฐ์ ์ผ๋ก ๊ฐ์ ธ์ต๋๋ค.</li>
> </ul>
> </details>
> <details>
> <summary>2. ์ถ์ฒ ์์ ์ ๋ณด ํ๋ฉด</summary>
> <img src="https://user-images.githubusercontent.com/92194918/221409122-a93723d2-a67d-45e8-ae72-fd12e5a1b14a.gif" width="240">
> <img src="https://user-images.githubusercontent.com/92194918/221409319-3f15645a-815e-40f5-9d53-7316305259ec.gif" width="240"/><br>
> <ul>
> <li><b>์ง๋ ์์ ์์ฑ๋ ์์ ํ์ ํด๋ฆญํ๋ฉด ํด๋น ์ฅ์์์ ์ถ์ฒ๋ ์์์ ์ ๋ณด๋ฅผ ํ์ธํ  ์ ์์ต๋๋ค.</b></li>
> <li>'ReadMoreTextView' ๋ผ์ด๋ธ๋ฌ๋ฆฌ๋ฅผ ์ฌ์ฉํ์ฌ ์ฌ์ฐ์ด 2์ค ์ด์์ผ ๊ฒฝ์ฐ ๋๋ณด๊ธฐ ํด๋ฆญ ์ ์ ์ฒด ํ์คํธ๊ฐ ํ์๋๋๋ก ๊ตฌํํ์ต๋๋ค.</li>
> <li>์จ๋ฒ ์ด๋ฏธ์ง์ ์ ํ๋ธ ๋ฒํผ์ ํด๋ฆญํ๋ฉด ํด๋น ์์์ "๊ฐ์ ๊ณก ์ ๋ชฉ"์ ๊ฒ์ํ ์ ํ๋ธ ํ๋ฉด์ผ๋ก ์ด๋ํฉ๋๋ค.</li>
> <li>์ฐ์ธก ์๋จ์ ์์ด์ฝ์ ๋ณธ์ธ ์์ฑ ์ฌ๋ถ, ๊ณต๊ฐํ๊ธฐ, ๊ณต์ ํ๊ธฐ ๋ฒํผ์ด๋ฉฐ ์ถํ ๊ตฌํ ์์ ์๋๋ค.</li>
> </ul>
> </details>
> <details>
> <summary>3. ์์ ์ถ์ฒํ๊ธฐ</summary>
> <img src="https://user-images.githubusercontent.com/92194918/221411387-e3c4104b-7729-4e47-bf41-35e0b7a12249.gif" width="240">
> <img src="https://user-images.githubusercontent.com/92194918/221411240-71db16af-92db-4bc4-9e54-ee71f23884e5.gif" width="240">
> <img src="https://user-images.githubusercontent.com/92194918/221411662-3435fe31-6919-42c4-bbb7-fd782c771798.gif" width="240">
> <img src="https://user-images.githubusercontent.com/92194918/221412025-374e2740-3d11-49cc-891f-8fe732f10c2f.gif" width="240"/><br>
> <ul>
> <li><b>์ฅ์ ์ ํ๋ถํฐ ์ฌ์ฐ ์๋ ฅ๊น์ง ์์ ์ถ์ฒํ๊ธฐ ๊ธฐ๋ฅ์ ์ผ๋ จ์ ๊ณผ์ ์๋๋ค.</b></li>
> <li>'๋ค๋ฅธ ์์น์์ ์ถ์ฒํ๊ธฐ' ํด๋ฆญ ์ ์ฒซ ๋ฒ์งธ ํ๋ฉด๋ถํฐ ์์ํ๋ฉฐ ํ์ฌ ์์น์์ ์ถ์ฒํ๊ธฐ ์ ๋ ๋ฒ์งธ ํ๋ฉด์์ ์์ํ๊ฒ ๋ฉ๋๋ค.</li>
> <li>Fragment ์ ํ ์ดํ์๋ ์ถ์ฒ ์์น, ์ ํํ ์์์ ๋ฐ์ดํฐ๋ฅผ ๋ณด์กดํ๊ธฐ ์ํด 'activityViewModels'๋ฅผ ์ฌ์ฉํ์ฌ ๋ฐ์ดํฐ๋ฅผ ์ ์งํ๋๋ก ํ์ต๋๋ค. </li>
> <li>์์ ๊ฒ์ํ๋ฉด์์ ์์ ๋ฐ์ดํฐ๋ 'ManiaDB API'๋ฅผ ์ฌ์ฉํ์ฌ ์์ ์ ๋ณด๋ฅผ ๊ฐ์ ธ์ค๋๋ก ํ์ต๋๋ค.</li>
> </ul>
> </details>
> <details>
> <summary>4. ์ง๋ญ๋ฃ ์ฐจํธ</summary>
> <img src="https://user-images.githubusercontent.com/92194918/221413642-fb41f8da-7f7d-4456-ad68-9fdee9f007eb.png" width="240"/><br>
> <ul> 
> <li><b>์ฌ์ฉ์์ ํ์ฌ ์์น(ํ์ ๊ตฌ์ญ)๋ฅผ ๊ธฐ์ค์ผ๋ก ํด๋น ์ง์ญ์์ ๊ณต๊ฐ์ ๋ง์ด ๋ฐ์ ์์ 10๊ฐ์ ์์์ ํ์ํฉ๋๋ค.</b></li>
> <li>์ถํ ๊ตฌํ ์์ ์๋๋ค.</li>
> </ul>
> </details>

<br>

## ๐ ๏ธ <I>How?</I> :: ๊ธฐ์  ์คํ <br>
<details>
  <summary>๐ค  Communication</summary>
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white">
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
  <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">
</details>
<details>
  <summary>๐ฅ๏ธ  Front End</summary>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=Android&logoColor=white">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white">
  <img src="https://img.shields.io/badge/Mac-FFFFFF?style=for-the-badge&logo=apple&logoColor=black">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Jetpack AAC-FF0000?style=for-the-badge&logo=&logoColor=white">
  <img src="https://img.shields.io/badge/MVVM-0F9D58?style=for-the-badge&logo=&logoColor=white">
  <img src="https://img.shields.io/badge/Coroutine-0F9D58?style=for-the-badge&logo=&logoColor=white">
  <img src="https://img.shields.io/badge/Retrofit-3E4348?style=for-the-badge&logo=Square&logoColor=white">
  <img src="https://img.shields.io/badge/OkHttp-3E4348?style=for-the-badge&logo=Square&logoColor=white">
  <img src="https://img.shields.io/badge/Glide4-008ED2?style=for-the-badge&logo=&logoColor=white">
  <img src="https://img.shields.io/badge/Google Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white">
  <img src="https://img.shields.io/badge/Mania DB-FF3366?style=for-the-badge&logo=music&logoColor=white">
</details>
<details>
  <summary>๐พ  Back End</summary>
  <img src="https://img.shields.io/badge/IntelliJ-000000?style=for-the-badge&logo=intellijidea&logoColor=white">
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/Java-FFFFFF?style=for-the-badge&logo=openjdk&logoColor=red">
  <img src="https://img.shields.io/badge/Mac-FFFFFF?style=for-the-badge&logo=apple&logoColor=black">
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black">
  <img src="https://img.shields.io/badge/MVC-0F9D58?style=for-the-badge&logo=&logoColor=white">
</details>

<br>

## ๐ฉโ๐ฉโ๐ฆ <I>Who?</I> :: Members
* Android ([GitHub](https://github.com/GMD-music-recommend-app/GMD-FE))
  + [๋ฏผ์ธ๋ฆผ](https://github.com/anonymousRecords) 
  + [์กฐ์ง์](https://github.com/jinsuCH0/) 
* Back ([GitHub](https://github.com/GMD-music-recommend-app/GMD-BE))
  + [๋ฐํฌ์](https://github.com/hw130) 
  + [์ ์กฐ์](https://github.com/joeun-01)
* UX/UI
  + [์ ์ง์](mailto:jinahyu210@gachon.ac.kr)
