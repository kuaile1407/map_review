# MCU 内存分析报告

生成时间: 2026-02-25 09:23:31

## 1. 内存使用概览

| 内存类型 | 已使用 | 最大值 | 使用率 |
|---------|--------|--------|--------|
| Flash (ROM) | 341.3 KB | 1.0 MB | 33.3% |
| SRAM (RAM) | 181.3 KB | 256.0 KB | 70.8% |

## 2. 详细分布

| 段 | 大小 |
|----|------|
| Code | 294.0 KB |
| RO Data | 42.4 KB |
| RW Data | 4.9 KB |
| ZI Data | 176.4 KB |
| Heap | 32.0 KB |
| Stack | 27.6 KB |

## 3. 段统计 (Top 10)

| 段名 | 大小 |
|------|------|
| text | 291.9 KB |
| noinit | 122.6 KB |
| bss | 51.3 KB |
| rodata | 41.8 KB |
| datas | 4.9 KB |
| sw_isr_table | 2.1 KB |
| rom_start | 1.1 KB |
| device_area | 720.0 B |
| log_const_area | 560.0 B |
| initlevel | 320.0 B |

## 4. 模块统计 (Top 10)

| 模块 | ROM | RAM |
|------|-----|-----|
| vice_controller_s140_debug_hardfp__obfuscated.elf) | 59.9 KB | 4.3 KB |
| zephyr/kernel/libkernel.a(mempool.c.obj) | 574.0 B | 32.0 KB |
| app/libapp.a(svc_storage.c.obj) | 4.2 KB | 26.3 KB |
| tooth/host/libsubsys__bluetooth__host.a(att.c.obj) | 10.8 KB | 15.6 KB |
| ooth/host/libsubsys__bluetooth__host.a(conn.c.obj) | 8.7 KB | 11.9 KB |
| /host/libsubsys__bluetooth__host.a(hci_core.c.obj) | 13.2 KB | 5.3 KB |
| at/libmpsl.a(libmpsl_debug_hardfp__obfuscated.elf) | 14.3 KB | 1.8 KB |
| rt/libsubsys__mgmt__mcumgr__transport.a(smp.c.obj) | 665.0 B | 14.6 KB |
| tooth/host/libsubsys__bluetooth__host.a(buf.c.obj) | 1.0 KB | 13.5 KB |
| ooth/host/libsubsys__bluetooth__host.a(gatt.c.obj) | 12.4 KB | 658.0 B |
