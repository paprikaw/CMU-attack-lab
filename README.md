# CMU-attack-lab
## Notion notes:
https://www.notion.so/baixucs/attack-lab-6318ecdacf46428abefd264c0d76f6a9

# 重要的指令:

从assmenly codes生成对应的hex decimal编码的值:

```gcc -c inject_codes.s & objdump -d inject_codes.o > inject_codes.d```

从hex decimal编码的值生成input string:

```./hex2raw < inject_codes.d > ans2_output```