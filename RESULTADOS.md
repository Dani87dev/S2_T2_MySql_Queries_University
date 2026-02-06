# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 4 correctas de 6 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,6 @@
 nombre | apellido1 | apellido2 | nif
+Esther | Spencer | Lakin | 61142000L
+Carmen | Streich | Hirthe | 85366986W
 Antonio | Fahey | Considine | 10485008K
 Guillermo | Ruecker | Upton | 85869555K
+Francesca | Schowalter | Muller | 79221403L
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.28 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 'NoneType' object is not iterable

