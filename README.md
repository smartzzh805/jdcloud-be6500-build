# JDCloud BE6500 (RE-CS-06) OAF build

Source: VIKINGYFY/immortalwrt @ 6b5baeb (firmware-exact commit, 2026-11-17).
This commit matches firmware r0-6b5baeb with libubox20261103 / libubus20261028.

Target: qualcommbe/ipq53xx/jdcloud_re-cs-06 (IPQ5322, kernel 6.18).

Goal: build standalone user-mode OAF packages (appfilter + luci-app-appfilter + zh-cn)
whose library ABI matches the running firmware exactly.

Releases contain per-run apk/ipk packages; use the one matching your firmware commit.
