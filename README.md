# Svelte V2 Snippets

The essential collection of Svelte V2 Snippets.



## Snippets

| Snippet           | Renders                             |
| ------------------| ------------------------------------|
| `svscript`        | Svelte Script                       |
| `svscriptfull`    | Svelte Script Extended              |
| `svexport`        | Svelte Export Default               |
| `svexportfull`    | Svelte Export Extended              |
| `svif`            | Svelte if block                     |
| `svifelse`        | Svelte if else block                |
| `svifelseif`      | Svelte if else if block             |
| `sveach`          | Svelte `each` block                 |
| `sveachelse`      | Svelte each else block              |
| `svoncreate`      | Svelte `oncreate` lifecycle method  |
| `svonstate`       | Svelte `onstate` lifecycle method   |
| `svonstateevent`  | Svelte `state` event                |
| `svonupdate`      | Svelte `onupdate` lifecycle method  |
| `svonupdateevent` | Svelte `update` event               |
| `svondestroy`     | Svelte `ondestroy` lifecycle method |
| `svevent`         | Svelte event                        |
| `svcomputed`      | Svelte `computed` properties wrapper|
| `svcomponents`    | Svelte `components` wrapper         |
| `svmethods`       | Svelte `methods` wrapper            |
| `svhelpers`       | Svelte `helpers` wrapper            |
| `svactions`       | Svelte `actions` wrapper            |
| `svget`  		      | `this.get()`                        |
| `svgetd`  		    | `this.get()` with declaration       |
| `svset`           | `this.set()`                        |

## Full Expansions

### svscript - Svelte Script

```html
<script>
  export default {
    data(){
      return {
        |
      }
    }
  }
</script>
```

### svscriptfull - Svelte Script Extended

```html
<script>

  import | from '|';

  export default {
    components:{
      |
    },
    computed:{
      |: ({|}) => |
    },
    data(){
      return {
        |
      }
    },
    oncreate(){
      var self = this;
      |
    },
    methods: {
      |
    }
  }
</script>
```

### svexport - Svelte Export

```javascript
  export default {
    data(){
      return {
        |
      }
    }
  }
```

### svexportfull - Svelte Export Extended

```javascript
  import | from '|';

  export default {
    components:{
      |
    },
    computed:{
      |: ({|}) => |
    },
    data(){
      return {
        |
      }
    },
    oncreate(){
      var self = this;
      |
    },
    methods: {
      |
    }
  }
```

### svif - Svelte Script

```javascript
  {#if }

  {:elseif}

  {:else}

  {/if}
```



### svif - Svelte if block

```javascript
  {#if |}
    |
  {/if}
```


### svifelse - Svelte if else block

```javascript
  {#if |}
    |
  {:else}
    |
  {/if}
```


### svif - Svelte if else if block

```javascript
  {#if |}
    |
  {:elseif}
    |
  {:else}
    |
  {/if}
```


### sveach - svelte each block

```javascript
  {#each | as |}
    |
  {/each}
```


### sveachelse - svelte each else block

```javascript
  {#each | as |}
    |
  {:else}
    |
  {/each}
```



### svoncreate - svelte oncreate lifecycle method

```javascript
  oncreate(){
    var self = this;
    |
  }
```

### svonstate - svelte onstate lifecycle method

```javascript
  onstate({changed, current, previous}){
    var self = this;
    |
  }
```

### svonupdate - svelte onupdate lifecycle method

```javascript
  onupdate({changed, current, previous}){
    var self = this;
    |
  }
```

### svondestroy - svelte ondestroy lifecycle method

```javascript
  ondestroy(){
    var self = this;
    |
  }
```

### svevent - svelte event

```javascript
  this.on('|', (|) => {
    |
  });
```

### svonstateevent - svelte `state` event

```javascript
  this.on('state', ({changed, current, previous}) => {
    |
  });
```

### svonupdateevent - svelte `update` event

```javascript
  this.on('update', ({changed, current, previous}) => {
    |
  });
```

### svcomputed - svelte computed properties wrapper

```javascript
  computed: {
    |: ({|}) => |
  },
```

### svmethods - svelte methods wrapper

```javascript
  methods: {
    |(){
      |
    }
  },
```

### svcomponents - svelte components wrapper

```javascript
  components: {
    |
  },
```


### svhelpers - svelte helpers wrapper

```javascript
  helpers: {
    |
  },
```

### svget - svelte `get` method

```javascript
  this.get()|;
```

### svgetd - svelte `get` method with declaration

```javascript
  var {|} = this|.get();
```

### svset - svelte `set` method

```javascript
  this.set({ | : | });
```

