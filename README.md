# iptools
IP相关工具


# 功能列表
```go
import "github.com/yanmengfei/iptools"

func iptools.IPRange2CIDRs(start net.IP, end net.IP) []*net.IPNet // IP范围转CIDRs
func iptools.DecToIpv4(dec int) net.IP  // 整数转IP
func iptools.IPv4ToDec(ipv4 net.IP) // IP转整数
```