# cerutti_unidad1

Este es un proyecto básico en Angular que cumple con la consigna de mostrar un mensaje de saludo con el nombre de una persona y permitir la edición dinámica del nombre a través de un input.

## Doble Binding

En este proyecto, hemos utilizado el concepto de **doble binding** proporcionado por Angular. El doble binding nos permite mantener sincronizados los datos entre la vista (HTML) y el componente (TypeScript). Esto se logra mediante el uso de la directiva `[(ngModel)]`, que permite enlazar los cambios en la vista con las propiedades del componente y viceversa.



## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/cerutti_unidad1.git
   cd cerutti_unidad1```
2. Instala las dependencias del proyecto:

  ```bash
  npm install
  ```

## Uso
Asegúrate de tener el Angular CLI instalado globalmente:

```bash
npm install -g @angular/cli
```
Inicia el servidor de desarrollo:
```bash
ng serve
```
Abre tu navegador y visita http://localhost:4200/. Verás la página con el mensaje de saludo y el input.

Escribe un nombre en el input y verás cómo el mensaje de saludo se actualiza automáticamente.