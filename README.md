### ℹ️ About
This is a fork of [NitescuLucian/wpjh](https://github.com/NitescuLucian/hacks/tree/main/wpjh)

### 🖳 Installation
Use [soar](https://github.com/pkgforge/soar) & Run:
```bash
soar add 'wpjson-parser#github.com.pkgforge-security.wpjson-parser'
```

### 🧰 Usage
```mathematica
!# Pipe a WordPress target from STDIN || Use HTTPx to Check Status Code & Length
echo "https://wordpress.tatget" | wpjson-parser | httpx -status-code -content-length -silent
```