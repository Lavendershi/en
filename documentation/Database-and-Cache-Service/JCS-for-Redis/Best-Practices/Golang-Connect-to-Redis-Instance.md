# Golang Connection
- step1: Download redis client of golang

<code>go get github.com/garyburd/redigo/redis</code>


- step2: Write test case

```
package main
 import (
     "fmt"
    "github.com/garyburd/redigo/redis"
)
func main() {
    host := "jredis-hb1-prod-957e3a3d-0d76-45d4-a896-706173208db2.jmiss.jcloud.com"//website displayed on the console
    port := 6379
    c, err := redis.Dial("tcp", fmt.Sprintf("%s:%d", host, port))
    if err != nil {
        fmt.Println("Connect to redis error", err)
        return
    }
    defer c.Close()
    _, err := c.Do("AUTH", "B69B341E5C669082EFCF2E405C626379")
    if err != nil {
        fmt.Println("redis auth failed: ", err)
        return
    }
    _, err := c.Do("SET", "key", "jcloud-redis")
    if err != nil {
        fmt.Println("redis set failed: ", err)
        return
    }
     _, err := c.Do("GET", "key")
    if err != nil {
        fmt.Println("redis get failed: ", err)
        return
    }
    //do other command...
}
```