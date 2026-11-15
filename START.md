# START HERE: бриф на генерацию сайта
Внешняя инструкция: работай СТРОГО в этом порядке, забирая файлы по ссылкам
(ссылки отдают чистый текст/картинки без авторизации).

1. Прочитай инструкции ОБА файла полностью, до начала работы:
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/SKILL_1.md
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/SKILL_2.md
2. Прочитай бриф и входные данные: https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/PROMPT_FINAL.txt
   (в брифе упомянуты "прикреплённые файлы" - игнорируй это: всё доступно
   по ссылкам из этого документа.)
3. Прочитай список фото с описаниями: https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos_manifest.json
4. Фотографии клиента. Используй ТОЛЬКО эти URL, подбирая слотам по смыслу
   описания; вставляй их напрямую в <img src="...">:
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chistyy_salon_avtomobilya_s_kozhanymi_sidenyami_i_zaschitnym.jpg  —  Чистый салон автомобиля с кожаными сиденьями и защитным ковриком.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/belyy_legkovoy_avtomobil_priparkovan_na_ulitse_goroda_v_soln.jpg  —  Белый легковой автомобиль припаркован на улице города в солнечный день.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/temnyy_krossover_v_pomeschenii_avtoservisa_pod_yarkimi_lampa.jpg  —  Темный кроссовер в помещении автосервиса под яркими лампами.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/sotrudnik_okleivaet_beluyu_mashinu_zaschitnoy_plenkoy_v_avto.jpg  —  Сотрудник оклеивает белую машину защитной пленкой в автомастерской.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chernyy_avtomobil_stoit_v_avtomasterskoy_ili_garazhe.jpg  —  Черный автомобиль стоит в автомастерской или гараже.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chernyy_avtomobil_v_avtoservise_ili_deteyling_tsentre.jpg  —  Черный автомобиль в автосервисе или детейлинг-центре.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chernyy_vnedorozhnik_priparkovan_na_ulitse_goroda_ryadom_s_d.jpg  —  Черный внедорожник припаркован на улице города рядом с домами.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/bordovyy_avtomobil_priparkovan_na_fone_zdaniya_avtoservisa.jpg  —  Бордовый автомобиль припаркован на фоне здания автосервиса.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chernyy_avtomobil_posle_deteylinga_stoit_v_bokse.jpg  —  Черный автомобиль после детейлинга стоит в боксе.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/speredi_snyat_siniy_gruzovoy_avtomobil_kompanii_na_ulitse.jpg  —  Спереди снят синий грузовой автомобиль компании на улице.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/snyata_perednyaya_chast_temno_serogo_avtomobilya_v_pomeschen.jpg  —  Снята передняя часть темно-серого автомобиля в помещении мастерской.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/master_rabotaet_s_chernym_avtomobilem_v_deteyling_studii.jpg  —  Мастер работает с черным автомобилем в детейлинг-студии
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/svezho_vymytyy_temnyy_avtomobil_v_pomeschenii_avtomoyki.jpg  —  Свежо вымытый тёмный автомобиль в помещении автомойки.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/temnyy_krossover_priparkovan_na_gorodskoy_ulitse_v_solnechny.jpg  —  Темный кроссовер припаркован на городской улице в солнечный день.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/belyy_avtomobil_v_bokse_avtoservisa_s_podsvetkoy.jpg  —  Белый автомобиль в боксе автосервиса с подсветкой.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/avtomobil_v_protsesse_okleyki_zaschitnoy_plenkoy_v_avtomaste.jpg  —  Автомобиль в процессе оклейки защитной пленкой в автомастерской.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/svetlyy_kozhanyy_salon_avtomobilya_posle_deteylinga_ili_himc.jpg  —  Светлый кожаный салон автомобиля после детейлинга или химчистки.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/krasnyy_avtomobil_priparkovan_na_ulitse_ryadom_s_drugimi_mas.jpg  —  Красный автомобиль припаркован на улице рядом с другими машинами.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/sboku_snyat_chistyy_chernyy_avtomobil_v_pomeschenii_avtoserv.jpg  —  Сбоку снят чистый черный автомобиль в помещении автосервиса.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/chernyy_avtomobil_priparkovan_u_punkta_zameny_masla_v_snezhn.jpg  —  Черный автомобиль припаркован у пункта замены масла в снежную погоду.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/svetlyy_kozhanyy_salon_avtomobilya_lexus_s_zadnimi_sidenyami.jpg  —  Светлый кожаный салон автомобиля Lexus с задними сиденьями.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/salon_avtomobilya_s_perednimi_sidenyami_i_rulevym_kolesom.jpg  —  Салон автомобиля с передними сиденьями и рулевым колесом.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/krupnyy_plan_perednego_kolesa_i_kryla_legkovogo_avtomobilya_.jpg  —  Крупный план переднего колеса и крыла легкового автомобиля в помещении.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/krupnyy_plan_zadney_fary_avtomobilya_na_ulitse_v_temnoe_vrem.jpg  —  Крупный план задней фары автомобиля на улице в темное время.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/krupnyy_plan_peredney_chasti_sinego_kommercheskogo_avtomobil.jpg  —  Крупный план передней части синего коммерческого автомобиля
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/salon_avtomobilya_s_perednimi_sidenyami_i_rulem_s_mehovoy_op.jpg  —  Салон автомобиля с передними сиденьями и рулем с меховой оплеткой.
   - https://raw.githubusercontent.com/inkoprog/brief-70000001089129207/main/photos/sravnenie_far_avtomobilya_do_i_posle_polirovki_v_avtoservise.jpg  —  Сравнение фар автомобиля до и после полировки в автосервисе.

# Фотографии и формат результата
- Фотографии: ТОЛЬКО URL из пункта 4, вставляй напрямую в <img src="...">.
  Никаких других картинок, стоков и генерации изображений.
- Верни сайт ПРОЕКТОМ ИЗ ТРЁХ ФАЙЛОВ: index.html, style.css, script.js
  (так, как это делает твоя среда, например в папке site итогового архива).
  Если бриф (PROMPT_FINAL.txt) требует отдать сайт ОДНИМ файлом или
  "одним артефактом в сообщении" - ИГНОРИРУЙ это требование: оно относится
  к другому конвейеру.
- Код в одно сообщение не сжимай и не сокращай.
