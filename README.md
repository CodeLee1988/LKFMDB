# LKFMDB
####对FMDB面向对象封装,支持任意类型主键，一键即可保存更新，用过的人都说好。


####支持SQLCipher加密 
      默认为加密模式  
      如需要取消在fmdb文件下FMDatabase.m文件下
      注释掉低150行和177行代码
      else{
       [self setKey:DB_SECRETKEY];
      }


/** 别名 */
@property (nonatomic, copy)  NSString *columnName;
/** 限制 */
@property (nonatomic, copy)  NSString *check;
/** 默认 */
@property (nonatomic, copy)  NSString *defaultValue;
/** 外键 */
@property (nonatomic, copy)  NSString *foreignKey;
