# SVG Shape Generator Project

## 🎯 Project Goal

To develop a modular Java-based system for creating, transforming, styling, and exporting 2D vector graphics using SVG markup.

---

## 📄 Description

This project allows defining and manipulating geometric shapes—such as points, lines, polygons, and ellipses—with SVG rendering. Users can apply visual styles (like fill and stroke), geometric transformations (rotate, scale, translate), and advanced SVG effects such as filters and gradients. The program supports saving the output as a standalone HTML file for display in browsers.

---

## ✨ Features

- **Geometric primitives**:
  - `Polygon` and `Ellipse`: SVG-renderable shapes

- **SVG generation**:
  - All shapes can be rendered via `.toSvg()` methods
  - `SvgScene`: manages a collection of shapes and saves to an HTML file

- **Styling system**:
  - `Style`: defines fill/stroke color and stroke width
  - Applied directly or via decorators

- **Advanced shape decorators**:
  - `SolidFillShapeDecorator`
  - `StrokeShapeDecorator`
  - `DropShadowDecorator` (adds shadow)
  - `GradientFillShapeDecorator` (adds linear gradients with custom stops)

- **Affine transformations**:
  - `TransformationDecorator` applies:
    - Translation
    - Rotation
    - Scaling
  - Built using fluent-style `Builder` pattern

- **Singleton pattern**:
  - `SvgScene` uses a singleton instance to maintain global shape state




![image](https://github.com/user-attachments/assets/d8b36550-4823-45de-af89-31d0ab8a5f86)

