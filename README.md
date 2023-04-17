# Digital filter designer

A website that helps users to design a custom digital filter via zeros-poles placement on the z-plane.

## Table of Contents

- [Deployment](#Deployment)
- [Design](#Design)
- [Features](#Features)

## Deployment
 Clone


 Install flask
```bash
  pip install flask
```
To start deployment 
```bash
  flask run
```

## 🖌️ Design

![main widow](./demo/home.png)

## Features
1. Add zeros

![main widow](./demo/add_zeros.gif)

2. Add poles

![main widow](./demo/add_poles.gif)

3. Modify the placed zeros/poles by dragging them

![main widow](./demo/drag.gif)

4. Click on a zero or pole and delete it

![main widow](./demo/delete.gif)

5. Delete all zeros and poles

![main widow](./demo/delete_all.gif)

6. Correct for the phase by adding some All-Pass filters

![main widow](./demo/add_all.gif)

7. Enable/disable the added all-pass elements

![main widow](./demo/apply_all.gif)

8. Generate signal to test your filter 

![main widow](./demo/generate.gif)

     All rights reserved © 2022 to Team 21 - Systems & Biomedical Engineering, Cairo University (Class 2024)
