<<<<<<< HEAD
# 01_Setup_Entorno

1. Instala Node y NPM
2. Inicializa un nuevo proyecto de node e instala jest
```bash
npm init -y
npm install --save-dev jest
```
3. Modifica `package.json` para que incluya este comando `test`:
```json
"scripts": {
  "test": "jest"
}
```
4. Crea un archivo `sumar.test.ts` y agrega este contenido
```typescript
test('prueba falsa', () => {
  expect(true).toBe(true);
});
```
5. Ejecuta la prueba con teste comando
```bash
npm test
```
=======
# 02 Entorno, Jest y primer test

Sigue las instrucciones delineadas en el [documento de la lección](https://hub.hybridge.education/doc/2-entorno-jest-y-primer-test-unitario-Vq9XIyWdew). Deberás crear los archivos necesarios y escribir la prueba unitaria que pruebe el endpoint `/tareas`.

Al terminar, toma una captura de pantalla de tu terminal con el resultado de la ejecución. Finalmente, sube tus cambios a tu repositorio de Github.
>>>>>>> 7ce53e33e109ef4887c6bb6e3d9133a8bdb99da6
