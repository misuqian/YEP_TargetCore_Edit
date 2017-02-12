##YEP_TargetCore_Edit
注意:本插件非YEP_TargetCore原版。

本插件修改了makeTargets，makeCustomTargets和getRandomTargets函数，使插件支持技能随机选择敌人时候不重复选择同一个敌人。

比如1：技能A范围为随机2个敌人，当前只有1个敌人A存活，则技能A只能对敌人A攻击有且仅有一次

比如2：技能A范围为随机2个敌人，当前只有3个敌人A,B,C存活，则技能A只能对敌人A,B,C中不同的2个人进行攻击

希望能帮助到你