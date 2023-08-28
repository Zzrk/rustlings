# rustlings

1. const 必须指明变量类型
2. 函数返回值类型通过 -> 指明
3. if 必须在 {..} 中
4. 数组元素必须是同类型的，let a: [u32; 100] = [0; 100];
5. &str 和 String 类型的区别
6. 模块同时导入多个 use std::time::{SystemTime, UNIX_EPOCH};
7. HashMap 类型：entry(key).or_insert(default_value)
8. Option/Result 解析出 Some/Ok 中的值用 unwrap()
9. if let Some(v) = .. / While let Some(v) = ..
10. Result 类型后添加 ?，会在 Err 类型自动返回
11. main 函数中添加返回类型 Result<(), Box<dyn Error>>，可以在其中使用 ?
12. impl<T> Wrapper<T> 声明 Wrapper 结构体中定义的是泛型而不是具体类型
13. 声明实现了某种 trait 的的类型可以用 impl Trait1 + Trait2 或者 Where ..
14. ？？iter() 和 into_iter() 的区别
15. ？？iter().map(..).collect() 会根据函数的返回值类型返回
16. (1..=num).fold(1, |acc, elem| acc * elem)
17. 智能指针，包括 Cow
18. #[macro_export]
19. clippy std::f32::consts::PI  std::mem::swap
20. from 和 into trait
21. from_str 和 parse trait
22. try_from 和 try_into trait
23. as_ref 和 as_mut trait