# Drop‑In Replacement: WireGuard Failover

## Overview
This relay replaces WireGuard’s default failover logic, delivering **sub‑1‑second recovery with zero packet loss**.

## Requirements
- Linux kernel ≥ 5.6
- WireGuard tools (`wg`, `wg-quick`)
- Python 3.10+ (for relay scripts)
- Root access

## Install
Clone the repo:
