# 🗒️ Registro de Trabajo en Clase - Taller X

## 📆 Fecha de la sesión
14/02/2026
## 👥 Integrantes presentes
- Santiago Soler 1
- Darek Aljuri
- Valentina Ruiz

## 🧠 Actividades realizadas en clase

Describa brevemente qué se hizo durante la sesión:

- ¿Qué se discutió con el equipo?

Al inicio no teníamos clara la diferencia entre un modelo entidad–relación y un diagrama entidad–relación (ERD). Primero construimos directamente el diagrama, pero luego entendimos que antes debíamos definir conceptualmente el modelo (entidades, atributos y relaciones) para después representarlo gráficamente. Esto nos permitió reorganizar mejor la información y estructurar el ERD de forma más coherente. Ademas de eso :
  - La diferencia entre modelo ER (conceptual) y diagrama ER (representación gráfica).
  - Cuáles eran las entidades principales del dominio: Paciente, Cita, Médico, Especialidad y Factura.
  - Cómo se relacionaban entre sí las entidades.
 
- ¿Qué decisiones de modelado se tomaron?
Se definieron las entidades principales con sus relaciones básicas:
  - Un paciente puede tener muchas citas.
  - Cada cita se asocia a un médico y a una especialidad.
  - Inicialmente habíamos conectado la entidad Factura con el módulo de Cliente (Paciente), pero luego corregimos el modelo y vinculamos la Factura con la Cita, ya que la facturación se genera a partir del servicio prestado en una cita específica.
  - También detectamos que habíamos modelado una relación muchos a muchos entre Médico y Especialidad. Para normalizar el modelo, decidimos romper esa relación creando una entidad intermedia llamada Medico_Especialidad, que permite representar correctamente que un médico puede tener varias especialidades y una especialidad puede estar asociada a varios médicos.

- ¿Qué herramientas se usaron (papel, pizarra, draw.io, Astah)?
  Draw.io

- ¿Qué parte del trabajo se alcanzó a desarrollar?
  - Se logró construir un modelo entidad–relación conceptual corregido.
  - Se desarrolló el ERD con las relaciones ajustadas (incluyendo la entidad intermedia Medico_Especialidad).
  - dSe elaboró un primer borrador del diagrama de contexto de negocio con actores, sistemas y principales flujos de información.

## 🧩 Boceto inicial del modelo
- Modelo Entidad Relacion
  <img width="837" height="668" alt="image" src="https://github.com/user-attachments/assets/3a154250-427d-4d23-b6ef-f46db3c7ec56" />
  
- Diagrama Entidad Relacion
<img width="1010" height="658" alt="image" src="https://github.com/user-attachments/assets/989ef95f-d029-49f7-bd61-6d155553208f" />

- Diagrama de contexto
<img width="1096" height="689" alt="image" src="https://github.com/user-attachments/assets/dbf2af0c-3fa0-456f-a4d8-b3be4a72645a" />

## 🔁 Tareas definidas para complementar el taller

Anote las responsabilidades acordadas entre los miembros del equipo para completar la entrega final:

| Tarea asignada | Responsable | Fecha estimada |
|----------------|-------------|----------------|
| Modelado final en draw.io | Darek Aljuri | 18/02 |
| Redacción del informe     | Valentina Ruiz | 18/02 |
| Investigación y referencias | Santiago Soler| 18/02 |

---

_Este documento resume el trabajo colaborativo realizado durante la sesión del taller X en el curso AREM - Universidad de La Sabana._
