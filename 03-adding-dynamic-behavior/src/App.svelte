<script>
  import Todos from './components/Todos.svelte'

  let todos = [
    { id: 1, name: 'Eat', completed: true },
    { id: 2, name: 'Swim', completed: true },
    { id: 3, name: 'Run', completed: false }
  ]
</script>

<Todos {todos}/>