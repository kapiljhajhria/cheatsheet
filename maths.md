Math Formula

**Distance Between two cartesian points**

```javascript
        
function getDistance(pointA, pointB) {
    let dx = pointA[0] - pointB[0];               // delta x
    let dy = pointA[1] - pointB[1];             // delta y
    let dist = Math.sqrt((dx * dx) + (dy * dy)); // distance
    return dist
}
```




