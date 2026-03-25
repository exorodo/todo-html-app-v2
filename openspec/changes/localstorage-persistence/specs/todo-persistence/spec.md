## todo-persistence
### Requirements
1. saveTodos(): localStorage.setItem
2. loadTodos(): JSON.parse || []
3. Save after each render
4. Load on init, render
### Scenarios
- Given saved todos, When refresh, Then reappear
- Given empty storage, When load, Then empty
