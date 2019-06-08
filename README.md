# 项目目标
验证java相关技术的特性

# 代码构成方式

- 同一个类别的验证放在一个maven的模块下面。比如 designPattern中的singleton模块表示设计模式中的单例模式
- 同一种策略的验证放在一个类，每个类都以Verify结尾,共享类放到各自功能的包下面。比如单例模式中对类加载的验证
- 对同一种策略的不同验证措施，放到不同的方法里面，每个方法验证一种情形。比如类加载验证中测试枚举和非枚举类
