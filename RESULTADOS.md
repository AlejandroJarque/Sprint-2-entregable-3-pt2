# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 16 correctas de 21 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.49 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,nif, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.24 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1 @@
 nombre
-Informática
-Matemáticas
-Economía y Empresa
-Educación
-Agronomía
-Química y Física
-Filología
-Derecho
-Biología y Geología
```

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,7 +1,4 @@
 departamento | total
-Educación | 3.00
-Informática | 2.00
-Matemáticas | 2.00
-Economía y Empresa | 2.00
-Química y Física | 2.00
+Economía y Empresa | 1.00
 Agronomía | 1.00
+Derecho | 1.00
```

⏱ Tiempo: 0.29 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 19: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
 departamento | total
-Informática | 2.00
-Matemáticas | 2.00
-Economía y Empresa | 2.00
-Educación | 3.00
+Economía y Empresa | 1.00
 Agronomía | 1.00
-Química y Física | 2.00
+Derecho | 1.00
+Informática | 0.00
+Matemáticas | 0.00
+Educación | 0.00
+Química y Física | 0.00
 Filología | 0.00
-Derecho | 0.00
 Biología y Geología | 0.00
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,11 +1,11 @@
-grau | total
-Grado en Ingeniería Informática (Plan 2015) | 51.00
-Grado en Biotecnología (Plan 2015) | 32.00
-Grado en Ingeniería Agrícola (Plan 2015) | 0.00
-Grado en Ingeniería Eléctrica (Plan 2014) | 0.00
-Grado en Ingeniería Electrónica Industrial (Plan 2010) | 0.00
-Grado en Ingeniería Mecánica (Plan 2010) | 0.00
-Grado en Ingeniería Química Industrial (Plan 2010) | 0.00
-Grado en Ciencias Ambientales (Plan 2009) | 0.00
-Grado en Matemáticas (Plan 2010) | 0.00
-Grado en Química (Plan 2009) | 0.00
+grado | total
+Grado en Ingeniería Agrícola (Plan 2015) | 1.00
+Grado en Ingeniería Eléctrica (Plan 2014) | 1.00
+Grado en Ingeniería Electrónica Industrial (Plan 2010) | 1.00
+Grado en Ingeniería Informática (Plan 2015) | 1.00
+Grado en Ingeniería Mecánica (Plan 2010) | 1.00
+Grado en Ingeniería Química Industrial (Plan 2010) | 1.00
+Grado en Biotecnología (Plan 2015) | 1.00
+Grado en Ciencias Ambientales (Plan 2009) | 1.00
+Grado en Matemáticas (Plan 2010) | 1.00
+Grado en Química (Plan 2009) | 1.00
```

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 21: Error
- **Descripción**: 'NoneType' object is not iterable

