![logo-dark](https://user-images.githubusercontent.com/58343999/124029514-3a022000-d9c3-11eb-8e40-1f4ee5774f3f.png)
# gantt-color-tasksv0.1
## A simple way to make a gantt chart for any purpose
## Usage
```
Just go to the folder "components", copy and paste Gantt.vue into your Vue project
```

### Parameters and how to setup this component
```
inside Gantt.vue, in the data, there gonna be something like this: 

```
![image](https://user-images.githubusercontent.com/58343999/124028959-9add2880-d9c2-11eb-8e64-a10746a38293.png)
### Here's an explanation for what's inside
```
clientes(customers): an array of objects that will go as option into the select box 
dataGantt: the data that's going to be inside the gantt chart
items: what's gonna be the name, assignment and real time spent on a given task,
it has nested items that will be explained in detail
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
