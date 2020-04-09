在线查看demo
- 未使用promise  https://kkkinlibrary.github.io/Countdown/countDown.html
- 使用promise版本 https://kkkinlibrary.github.io/Countdown/countDown1.html


- 分别实现了用promise和不用promise的两个版本，原来打算链式调用promise的方法不可行，最后采用settimeout+递归的方式。
- 此外还有考虑到每次的时间误差都有数毫秒，累加起来不一会儿就会特别大。因此每次settimeout时都会将误差去掉避免时间误差的累积。