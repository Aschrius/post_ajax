# ???
刚好要把坑填完了
整理一些同事的问题，以后做解答


# Q1. post请求与ajax有什么区别？在springmvc开发上有什么异同？
听到的时候有点蒙蔽，ajax也可以发送post请求，具体的业务在写法上有些不同，在我当时看来，post请求是ajax的子集这类。有疑问后面再修改吧。[17.05.25]


# Q2. oracle中in影响性能，建议用or，但是如果需要or 100乃至需要拼接更多or的时候需要如何解决呢？



# Q3. 大数据再分页上如何解决？
今天项目遇到一个之前别人写的sql，发现速度巨慢无比。
select * from A a,B b where a.p=b.p and a.r=? and a.s=? group by createDate desc
外面再嵌套一层分页，这个明天需要解决，先丢在这里记录下。

# Q3. where in() 这里的东西非常之多的时候，要怎么处理？暂时用left join来。。。
