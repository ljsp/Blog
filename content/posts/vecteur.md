---
title: "Les Vecteurs"
date: 2023-12-17T21:45:25+01:00
draft: false
categories: ["maths"]
tags: ["maths"]
---

![Un vecteur](../../img/Vecteurs_somme.png "Un vecteur")

Un vecteur est une flèche qui pointe dans une direction et qui est défini par n valeurs pour la dimension n.

## Le produit vectoriel (cross) 

$\vec{a} \times \vec{b} = |a||b|\sin\theta\hat{n}$

## Le produit scalaire (dot)

``` C++
float dot( const Vector& u, const Vector& v )
{
    return u.x * v.x + u.y * v.y + u.z * v.z;
}
```


