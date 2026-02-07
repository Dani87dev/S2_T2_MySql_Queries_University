# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 6 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.46 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,217 @@
 apellido1 | apellido2 | nombre | departamento
+Sánchez | Pérez | Salvador | Biología y Geología
+Sánchez | Pérez | Salvador | Derecho
+Sánchez | Pérez | Salvador | Filología
+Sánchez | Pérez | Salvador | Química y Física
+Sánchez | Pérez | Salvador | Agronomía
+Sánchez | Pérez | Salvador | Educación
+Sánchez | Pérez | Salvador | Economía y Empresa
+Sánchez | Pérez | Salvador | Matemáticas
+Sánchez | Pérez | Salvador | Informática
+Saez | Vega | Juan | Biología y Geología
+Saez | Vega | Juan | Derecho
+Saez | Vega | Juan | Filología
+Saez | Vega | Juan | Química y Física
+Saez | Vega | Juan | Agronomía
+Saez | Vega | Juan | Educación
+Saez | Vega | Juan | Economía y Empresa
+Saez | Vega | Juan | Matemáticas
+Saez | Vega | Juan | Informática
+Ramirez | Gea | Zoe | Biología y Geología
+Ramirez | Gea | Zoe | Derecho
+Ramirez | Gea | Zoe | Filología
+Ramirez | Gea | Zoe | Química y Física
+Ramirez | Gea | Zoe | Agronomía
+Ramirez | Gea | Zoe | Educación
+Ramirez | Gea | Zoe | Economía y Empresa
+Ramirez | Gea | Zoe | Matemáticas
+Ramirez | Gea | Zoe | Informática
+Heller | Pagac | Pedro | Biología y Geología
+Heller | Pagac | Pedro | Derecho
+Heller | Pagac | Pedro | Filología
+Heller | Pagac | Pedro | Química y Física
+Heller | Pagac | Pedro | Agronomía
+Heller | Pagac | Pedro | Educación
+Heller | Pagac | Pedro | Economía y Empresa
+Heller | Pagac | Pedro | Matemáticas
+Heller | Pagac | Pedro | Informática
+Schmidt | Fisher | David | Biología y Geología
+Schmidt | Fisher | David | Derecho
+Schmidt | Fisher | David | Filología
+Schmidt | Fisher | David | Química y Física
+Schmidt | Fisher | David | Agronomía
+Schmidt | Fisher | David | Educación
+Schmidt | Fisher | David | Economía y Empresa
+Schmidt | Fisher | David | Matemáticas
+Schmidt | Fisher | David | Informática
+Koss | Bayer | José | Biología y Geología
+Koss | Bayer | José | Derecho
+Koss | Bayer | José | Filología
+Koss | Bayer | José | Química y Física
+Koss | Bayer | José | Agronomía
+Koss | Bayer | José | Educación
+Koss | Bayer | José | Economía y Empresa
+Koss | Bayer | José | Matemáticas
+Koss | Bayer | José | Informática
+Strosin | Turcotte | Ismael | Biología y Geología
+Strosin | Turcotte | Ismael | Derecho
+Strosin | Turcotte | Ismael | Filología
+Strosin | Turcotte | Ismael | Química y Física
+Strosin | Turcotte | Ismael | Agronomía
+Strosin | Turcotte | Ismael | Educación
+Strosin | Turcotte | Ismael | Economía y Empresa
+Strosin | Turcotte | Ismael | Matemáticas
+Strosin | Turcotte | Ismael | Informática
+Lemke | Rutherford | Cristina | Biología y Geología
+Lemke | Rutherford | Cristina | Derecho
+Lemke | Rutherford | Cristina | Filología
+Lemke | Rutherford | Cristina | Química y Física
+Lemke | Rutherford | Cristina | Agronomía
+Lemke | Rutherford | Cristina | Educación
+Lemke | Rutherford | Cristina | Economía y Empresa
+Lemke | Rutherford | Cristina | Matemáticas
+Lemke | Rutherford | Cristina | Informática
+Herzog | Tremblay | Ramón | Biología y Geología
+Herzog | Tremblay | Ramón | Derecho
+Herzog | Tremblay | Ramón | Filología
+Herzog | Tremblay | Ramón | Química y Física
+Herzog | Tremblay | Ramón | Agronomía
+Herzog | Tremblay | Ramón | Educación
+Herzog | Tremblay | Ramón | Economía y Empresa
+Herzog | Tremblay | Ramón | Matemáticas
+Herzog | Tremblay | Ramón | Informática
+Spencer | Lakin | Esther | Biología y Geología
+Spencer | Lakin | Esther | Derecho
+Spencer | Lakin | Esther | Filología
+Spencer | Lakin | Esther | Química y Física
+Spencer | Lakin | Esther | Agronomía
+Spencer | Lakin | Esther | Educación
+Spencer | Lakin | Esther | Economía y Empresa
+Spencer | Lakin | Esther | Matemáticas
+Spencer | Lakin | Esther | Informática
+Herman | Pacocha | Daniel | Biología y Geología
+Herman | Pacocha | Daniel | Derecho
+Herman | Pacocha | Daniel | Filología
+Herman | Pacocha | Daniel | Química y Física
+Herman | Pacocha | Daniel | Agronomía
+Herman | Pacocha | Daniel | Educación
+Herman | Pacocha | Daniel | Economía y Empresa
+Herman | Pacocha | Daniel | Matemáticas
+Herman | Pacocha | Daniel | Informática
+Streich | Hirthe | Carmen | Biología y Geología
+Streich | Hirthe | Carmen | Derecho
+Streich | Hirthe | Carmen | Filología
+Streich | Hirthe | Carmen | Química y Física
+Streich | Hirthe | Carmen | Agronomía
+Streich | Hirthe | Carmen | Educación
+Streich | Hirthe | Carmen | Economía y Empresa
+Streich | Hirthe | Carmen | Matemáticas
+Streich | Hirthe | Carmen | Informática
+Stiedemann | Morissette | Alfredo | Biología y Geología
+Stiedemann | Morissette | Alfredo | Derecho
+Stiedemann | Morissette | Alfredo | Filología
+Stiedemann | Morissette | Alfredo | Química y Física
+Stiedemann | Morissette | Alfredo | Agronomía
+Stiedemann | Morissette | Alfredo | Educación
+Stiedemann | Morissette | Alfredo | Economía y Empresa
+Stiedemann | Morissette | Alfredo | Matemáticas
+Stiedemann | Morissette | Alfredo | Informática
+Hamill | Kozey | Manolo | Biología y Geología
+Hamill | Kozey | Manolo | Derecho
+Hamill | Kozey | Manolo | Filología
+Hamill | Kozey | Manolo | Química y Física
+Hamill | Kozey | Manolo | Agronomía
+Hamill | Kozey | Manolo | Educación
+Hamill | Kozey | Manolo | Economía y Empresa
+Hamill | Kozey | Manolo | Matemáticas
+Hamill | Kozey | Manolo | Informática
+Kohler | Schoen | Alejandro | Biología y Geología
+Kohler | Schoen | Alejandro | Derecho
+Kohler | Schoen | Alejandro | Filología
+Kohler | Schoen | Alejandro | Química y Física
+Kohler | Schoen | Alejandro | Agronomía
+Kohler | Schoen | Alejandro | Educación
+Kohler | Schoen | Alejandro | Economía y Empresa
+Kohler | Schoen | Alejandro | Matemáticas
+Kohler | Schoen | Alejandro | Informática
+Fahey | Considine | Antonio | Biología y Geología
+Fahey | Considine | Antonio | Derecho
+Fahey | Considine | Antonio | Filología
+Fahey | Considine | Antonio | Química y Física
+Fahey | Considine | Antonio | Agronomía
+Fahey | Considine | Antonio | Educación
 Fahey | Considine | Antonio | Economía y Empresa
-Hamill | Kozey | Manolo | Informática
-Kohler | Schoen | Alejandro | Matemáticas
-Lemke | Rutherford | Cristina | Economía y Empresa
+Fahey | Considine | Antonio | Matemáticas
+Fahey | Considine | Antonio | Informática
+Ruecker | Upton | Guillermo | Biología y Geología
+Ruecker | Upton | Guillermo | Derecho
+Ruecker | Upton | Guillermo | Filología
+Ruecker | Upton | Guillermo | Química y Física
+Ruecker | Upton | Guillermo | Agronomía
+Ruecker | Upton | Guillermo | Educación
+Ruecker | Upton | Guillermo | Economía y Empresa
+Ruecker | Upton | Guillermo | Matemáticas
+Ruecker | Upton | Guillermo | Informática
+Monahan | Murray | Micaela | Biología y Geología
+Monahan | Murray | Micaela | Derecho
+Monahan | Murray | Micaela | Filología
+Monahan | Murray | Micaela | Química y Física
 Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
+Monahan | Murray | Micaela | Educación
+Monahan | Murray | Micaela | Economía y Empresa
+Monahan | Murray | Micaela | Matemáticas
+Monahan | Murray | Micaela | Informática
+Lakin | Yundt | Inma | Biología y Geología
+Lakin | Yundt | Inma | Derecho
+Lakin | Yundt | Inma | Filología
+Lakin | Yundt | Inma | Química y Física
+Lakin | Yundt | Inma | Agronomía
+Lakin | Yundt | Inma | Educación
+Lakin | Yundt | Inma | Economía y Empresa
+Lakin | Yundt | Inma | Matemáticas
+Lakin | Yundt | Inma | Informática
+Schowalter | Muller | Francesca | Biología y Geología
+Schowalter | Muller | Francesca | Derecho
+Schowalter | Muller | Francesca | Filología
 Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
+Schowalter | Muller | Francesca | Agronomía
+Schowalter | Muller | Francesca | Educación
+Schowalter | Muller | Francesca | Economía y Empresa
+Schowalter | Muller | Francesca | Matemáticas
+Schowalter | Muller | Francesca | Informática
+Gutiérrez | López | Juan | Biología y Geología
+Gutiérrez | López | Juan | Derecho
+Gutiérrez | López | Juan | Filología
+Gutiérrez | López | Juan | Química y Física
+Gutiérrez | López | Juan | Agronomía
+Gutiérrez | López | Juan | Educación
+Gutiérrez | López | Juan | Economía y Empresa
+Gutiérrez | López | Juan | Matemáticas
+Gutiérrez | López | Juan | Informática
+Domínguez | Guerrero | Antonio | Biología y Geología
+Domínguez | Guerrero | Antonio | Derecho
+Domínguez | Guerrero | Antonio | Filología
+Domínguez | Guerrero | Antonio | Química y Física
+Domínguez | Guerrero | Antonio | Agronomía
+Domínguez | Guerrero | Antonio | Educación
+Domínguez | Guerrero | Antonio | Economía y Empresa
+Domínguez | Guerrero | Antonio | Matemáticas
+Domínguez | Guerrero | Antonio | Informática
+Hernández | Martínez | Irene | Biología y Geología
+Hernández | Martínez | Irene | Derecho
+Hernández | Martínez | Irene | Filología
+Hernández | Martínez | Irene | Química y Física
+Hernández | Martínez | Irene | Agronomía
+Hernández | Martínez | Irene | Educación
+Hernández | Martínez | Irene | Economía y Empresa
+Hernández | Martínez | Irene | Matemáticas
+Hernández | Martínez | Irene | Informática
+Gea | Ruiz | Sonia | Biología y Geología
+Gea | Ruiz | Sonia | Derecho
+Gea | Ruiz | Sonia | Filología
+Gea | Ruiz | Sonia | Química y Física
+Gea | Ruiz | Sonia | Agronomía
+Gea | Ruiz | Sonia | Educación
+Gea | Ruiz | Sonia | Economía y Empresa
+Gea | Ruiz | Sonia | Matemáticas
+Gea | Ruiz | Sonia | Informática
```

⏱ Tiempo: 0.48 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
🚨 `JOIN` sin índice. Revisar claves foráneas e índices.

---
