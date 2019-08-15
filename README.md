# Customize-PrimeNG-Theme
Customize PrimeNG Theme

# Requirements
- Angular 7+
- PrimeNG V8

# Instructions
1. Copy directory **nova-light** in **src/assets**
2. in **angular.json**
```JSON
    "styles": [
              "src/styles.css",
              "./node_modules/primeicons/primeicons.css",
              "src/assets/nova-light/theme.css",
              "./node_modules/primeng/resources/primeng.min.css"
            ],
```

3. in **src/assets/nova-light/colors.css** modify the colors

# Example:
  ```Stylus
  --v1: #107584;
  --v2: #0c5d69;
  --v3: #09464f;
  ```
