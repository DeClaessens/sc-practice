# Exercise (Thanks Peter!)

Create the Button component with:

- Colors
  - Primary background-color: #009996, color = white
  - Secondary background-color: #F8D402, color = #006B6E
  - Tertiary background-color: #f2f2f2, color = #000
- Normal, Hover (10% darker) and Disabled (0.3 opacity) state
- Sizes
  - normal: height: 40px, padding: 12px
  - large: height: 64px, padding: 24px
  - small: height: 32px, padding: 8px

# Primary/Secodary

<img src="./images/styling-button1.png" />

# Sizes

<img src="./images/styling-button-sizes.png" />

# JSX

```jsx
<!-- Primary (green), default size (40px) -->
<Button>Standard</Button>

<!-- Secondary (yellow), default size (40px) -->
<Button variant="secondary">Secondary</Button>

<!-- Tertiary (grey), default size (40px) -->
<Button variant="tertiary">Secondary</Button>

<!-- Primary (green), large size (64px) -->
<Button size="large">Large</Button>

<!-- Primary (green), small size (32px) -->
<Button size="small">Small</Button>

<!-- Primary (green), default size (32px), disabled -->
<Button disabled>Disabled</Button>
```
