# FIXME
1. 實作 Delete
2. 優化 Component 每個動作都會 rerender

# 練習目標重點
- 按下刪除後，需正確刪除該筆 Todo。
- TodoItem 的 props 需正確定義型別(flowjs 或是 propsTypes 皆可)
- `TodoItem`、`TodoForm`、`TodoFilter` 需使用 `React.memo` 包起來。
- TodoList 裡的 `onAddTodo`、`onToggleTodo` 需使用 `React.useCallback` 包起來。