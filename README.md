# analisis_apps
# 📊 Análisis de Comportamiento de Usuarios en Aplicaciones

## 📌 Problemática

En el contexto de una empresa que ofrece tres aplicaciones distintas (BR, UH y SO), es fundamental comprender el comportamiento de los usuarios en cada una de ellas. Esta información es crucial para tomar decisiones en cuanto a mejoras de las aplicaciones, estrategias de marketing y toma de decisiones empresariales. En este repositorio, abordaremos esta problemática mediante un análisis detallado de los datos recopilados de las tres aplicaciones.

## 📁 Contenido del Repositorio

Este repositorio contiene los siguientes elementos:

### 📝 Notebooks

1. **`datos_gestion.ipynb`**: En este cuaderno de Colab, encontrará el código utilizado para limpiar, transformar, analizar los datos y generar visualizaciones relevantes. Exploraremos el comportamiento de los usuarios en las tres aplicaciones, identificando tendencias y patrones clave.

2. **`SQL proyecto.ipynb`**: Este cuaderno contiene consultas SQL escritas en Python utilizando SQLite3. Estas consultas se utilizan para practicar temas vistos en clase con una base de datos real.

### 📊 Conjunto de Datos

El conjunto de datos utilizado en este proyecto contiene:

- **Cantidad de Datos**: 305,386 registros.
- **Tipo de Datos**: La información se refiere al comportamiento de los usuarios en tres aplicaciones empresariales.
- **Número de Características**: El conjunto de datos consta de 17 columnas que capturan diversas métricas y características de los usuarios y su interacción con las aplicaciones.
  A continuación, se presenta una descripción concisa de las columnas de la base de datos en formato de tabla para incluir en el README de GitHub:

| Columna                      | Descripción                                     |
|------------------------------|-------------------------------------------------|
| event_date                   | Fecha del evento registrado.                    |
| event_timestamp              | Marca de tiempo del evento.                     |
| event_name                   | Nombre del evento registrado.                   |
| event_previous_timestamp     | Marca de tiempo del evento anterior.            |
| user_pseudo_id               | Identificador pseudónimo del usuario.           |
| user_first_touch_timestamp   | Marca de tiempo del primer contacto del usuario.|
| platform                     | Plataforma utilizada (p. ej., iOS, Android).    |
| event_year                   | Año en que ocurrió el evento.                   |
| event_month                  | Mes en que ocurrió el evento.                   |
| device_type                  | Tipo de dispositivo (p. ej., smartphone).       |
| brand                        | Marca del dispositivo.                          |
| continent                    | Continente donde se registró el evento.         |
| country                      | País donde se registró el evento.               |
| region                       | Región geográfica específica.                   |
| city                         | Ciudad donde se registró el evento.             |
| sub_continent                | Subcontinente donde se registró el evento.      |
| app                          | Nombre de la aplicación relacionada al evento.  |


## 🚀 Objetivos

El objetivo principal de este proyecto es proporcionar una visión detallada y completa del comportamiento de los usuarios en las tres aplicaciones empresariales. A través del análisis de datos buscamoes generar información valiosa para la toma de decisiones estratégicas.

## 📊 Resultados del Análisis

Tras el exhaustivo análisis de las tres aplicaciones, se han identificado las siguientes conclusiones significativas:

1. **Dominio del Mercado**: Entre las tres aplicaciones, se destaca que la aplicación "App UH" domina el mercado, a pesar de que todas ellas comparten el mismo objetivo.

2. **Tendencias de Crecimiento**:
   - La aplicación "App SO" presenta una tendencia de crecimiento constante, con una ligera disminución en el mes de mayo.
   - La aplicación "App UH" se mantiene estable en términos de uso a lo largo del tiempo.
   - En contraste, la aplicación "App BR" muestra una tendencia a la disminución de su uso.

3. **Prevalencia de Evento**:
   - En todas las aplicaciones, se destaca que el evento "User Engagement" es el más prevalente entre los usuarios.

4. **Dispositivos Preferidos**:
   - Las tres aplicaciones son mayormente utilizadas en dispositivos móviles en lugar de tabletas.

5. **Plataforma de Uso**:
   - En la plataforma Android, la aplicación "App UH" es la más utilizada.
   - Por otro lado, en iOS, la aplicación "SO" se posiciona como la más utilizada.

6. **Preferencia de Marca**:
   - En cuanto a la marca de dispositivos, "App UH" es preferida por usuarios con dispositivos Samsung, mientras que "App BR" y "SO" son más populares entre los usuarios de iPhone.

7. **Países con Mayor Uso**:
   - Colombia lidera como el país con mayor uso de las aplicaciones, seguido de Estados Unidos.


## 🎯 Estrategias

1. **Enfocar Estrategias en App UH**: Dado su dominio en el mercado, es crucial dirigir los esfuerzos de marketing hacia la aplicación "App UH". Esto podría incluir campañas publicitarias específicas y promociones para aumentar aún más su presencia.

2. **Aprovechar Tendencia de Crecimiento en App SO**: Aprovechar la tendencia de crecimiento constante de la aplicación "SO" es esencial. Se pueden implementar estrategias de retención de usuarios y mejoras específicas en esta aplicación para fomentar un crecimiento continuo.

3. **Segmentar por Plataforma y Marca**: Debido a las diferencias en la preferencia de plataforma y marca, se deben crear estrategias de marketing específicas para Android y iOS, así como para dispositivos Samsung y iPhone. Esto garantizará un enfoque más efectivo en cada grupo de usuarios.

Estas estrategias basadas en los datos ayudarán a maximizar el impacto del marketing y a mejorar la experiencia de los usuarios en todas las aplicaciones.

---
**¡Esperamos que este análisis sea útil y brinde una visión valiosa del comportamiento de los usuarios en las aplicaciones empresariales!**
