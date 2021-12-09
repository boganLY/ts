# ts tips

1. `!`非空断言，不能为`null` 或者`undefined` 
   ```typescript
   const form = useContext(EditableContext);
   // const form: FormInstance<any> | null
   const form = useContext(EditableContext)!;
   // const form: FormInstance<any>
   ```
   
   
