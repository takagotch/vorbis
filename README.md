### vorbis
---
https://github.com/mccoyst/vorbis

```go
// vorbis.go

func Decode(b []byte) (data []int16, channels int, sampleRate int, err error) {
  if len(b) == 0 {
    return
  }
  
  raw := (*C.unchar)(unsafe.Pointer(&b[0]))
  
}
```

```
```

```
```


