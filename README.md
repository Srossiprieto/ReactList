# Notas sobre React

## 1. ¿Por qué React?
- **Enrutamiento:**
  - `react-router-dom`
  - Guard
  - Enrutamiento a nivel hijos
  - Obtener datos de la URL (queryParams)

## 2. Manejo de Estados
- **Context:**
  - Global state
  - Por página
  - `useReducer`
- **Redux:**
  - Redux Toolkit
  - Redux Query
- **SWR (State While Revalidate)**
- **Zustand**
- **Jotai**

## 3. Comparaciones
- Diferencia entre `ReactNode` y `JSX.Element`
- `useMemo` vs `useCallback` vs `useRef`

## 4. Detección de Cambios
- Cuándo hay un cambio
- Cómo impacta el modo estricto
- Cosas que se pueden hacer para controlar un re-render no deseado:
  - Parámetros
  - Cambio
  - Montaje
  - Cambio de estado
  - Cambio de parámetros
  - Commit

## 5. Mejores Formas de Compartir Información entre Componentes
- De **Componente Padre** a **Hijo**:
  - Prop drilling
  - Composition pattern
- De **Componente** a **Componente Hermano**:
  - Observables
  - Servicio

## 6. Batching de Estados
- `setState`: `(setState => lógica al state)`

## 7. Cambios en React 19
- El nuevo compilador de React 19
- Qué cosas cambian con React 19

## 8. Hooks
- `useState`
- `useEffect`:
  - Cuándo utilizarlo correctamente
  - Qué va dentro del arreglo de dependencias
  - Qué pasa si quiero ejecutar un método `async`

## 9. Formularios en React
- **react-hook-form**:
  - Validación con schema:
    - `zod`
    - `yup`

## 10. Modelado con TypeScript

## 11. Arquitectura Utilizada
- Scream Architecture
- Clean Architecture
- Container/Presentational Architecture

## 12. Peticiones HTTP
- **Axios**:
  - Interrupt
  - API

## 13. Funcionalidades Adicionales de React
- Portals
- High Order Components
- Custom Hooks:
  - Cuándo utilizarlos
  - Qué conlleva
- Suspense y Lazy:
  - Qué significa

## 14. Estilos en React
- **Tipos de Styling**:
  - CSS Modules / SCSS
  - Variable styles
  - Objetos en el inline style

## 15. Manejo de Errores
- **ErrorBoundary**
