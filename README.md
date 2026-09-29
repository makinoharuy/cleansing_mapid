### Urutan Pembacaan Repository – Cleansing Data

Urutan folder/proses pembacaan data dalam repository adalah sebagai berikut:

**`MAPID_CLEANSINGDATA` → `CLEANSING_2` → `SOFT_OF_SPPG` → `FINAL_MERGE_DATA` → `CORRECTED_GEOJSON`**

Dengan penjelasan singkat:

1. **MAPID_CLEANSINGDATA**
   → Data awal hasil proses cleansing dan pengecekan kesesuaian data.

2. **CLEANSING_2**
   → Data yang telah melalui proses cleansing lanjutan atau perapihan lebih lanjut.

3. **SOFT_OF_SPPG**
   → Data/output yang berkaitan dengan SPPG dan digunakan sebagai bagian dari proses pengolahan berikutnya.

4. **FINAL_MERGE_DATA**
   → Data hasil penggabungan dari beberapa sumber/data yang telah diproses sebelumnya, dalam format seperti **CSV dan GeoJSON**.

5. **CORRECTED_GEOJSON**
   → **Output akhir**, yaitu data GeoJSON yang telah dilakukan koreksi dan siap digunakan.

**Alur sederhananya:**

`Data Awal`
↓
`MAPID_CLEANSINGDATA`
↓
`CLEANSING_2`
↓
`SOFT_OF_SPPG`
↓
`FINAL_MERGE_DATA`
↓
`CORRECTED_GEOJSON`
↓
**Final Data**
