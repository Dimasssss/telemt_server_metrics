# Server Metrics 2026-03-04 04:11:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 25260.3 (7h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167111
telemt_connections_bad_total 1617
telemt_handshake_timeouts_total 2920
telemt_upstream_connect_attempt_total 18515
telemt_upstream_connect_success_total 18438
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 18438
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8013
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 199
telemt_me_reconnect_attempts_total 4288
telemt_me_reconnect_success_total 4273
telemt_me_reader_eof_total 4375
telemt_me_idle_close_by_peer_total 4375
telemt_me_route_drop_no_conn_total 55628
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 417
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 5
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 4375
telemt_me_writer_restored_same_endpoint_total 4253
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 158840
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 1560434332 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 49035682608 (45.67 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 25257.0 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78972
telemt_connections_bad_total 299
telemt_handshake_timeouts_total 20379
telemt_upstream_connect_attempt_total 61145
telemt_upstream_connect_success_total 60523
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 60517
telemt_upstream_connect_attempts_per_request{bucket="2"} 301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19175
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_keepalive_timeout_total 947
telemt_me_reconnect_attempts_total 38425
telemt_me_reconnect_success_total 38399
telemt_me_reader_eof_total 39377
telemt_me_idle_close_by_peer_total 39376
telemt_me_route_drop_no_conn_total 24718
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 190
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 39438
telemt_me_writer_restored_same_endpoint_total 38378
telemt_me_writer_removed_unexpected_minus_restored_total 1060
telemt_user_connections_total{user="hello"} 57207
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 471300124 (449.47 MB)
telemt_user_octets_to_client{user="hello"} 27241896500 (25.37 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 25255.7 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179170
telemt_connections_bad_total 65230
telemt_handshake_timeouts_total 4151
telemt_upstream_connect_attempt_total 33590
telemt_upstream_connect_success_total 33371
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 33371
telemt_upstream_connect_attempts_per_request{bucket="2"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 13852
telemt_me_reconnect_success_total 13819
telemt_me_reader_eof_total 14554
telemt_me_idle_close_by_peer_total 14551
telemt_me_route_drop_no_conn_total 35536
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 109
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 14559
telemt_me_writer_restored_same_endpoint_total 13798
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 106166
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 673935644 (642.72 MB)
telemt_user_octets_to_client{user="hello"} 27785330588 (25.88 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 25254.5 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88617
telemt_connections_bad_total 3536
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 17386
telemt_upstream_connect_success_total 17309
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 17309
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 2772
telemt_me_reconnect_success_total 2774
telemt_me_reader_eof_total 2796
telemt_me_idle_close_by_peer_total 2796
telemt_me_route_drop_no_conn_total 29317
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 104
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 2796
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 80225
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 692775644 (660.68 MB)
telemt_user_octets_to_client{user="hello"} 27184973036 (25.32 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 25253.3 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197825
telemt_connections_bad_total 3139
telemt_handshake_timeouts_total 90483
telemt_upstream_connect_attempt_total 37639
telemt_upstream_connect_success_total 37388
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 37388
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 531
telemt_me_reconnect_attempts_total 18732
telemt_me_reconnect_success_total 18724
telemt_me_reader_eof_total 19824
telemt_me_idle_close_by_peer_total 19823
telemt_me_route_drop_no_conn_total 48360
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 132
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 19835
telemt_me_writer_restored_same_endpoint_total 18700
telemt_me_writer_removed_unexpected_minus_restored_total 1135
telemt_user_connections_total{user="hello"} 100542
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 644426272 (614.57 MB)
telemt_user_octets_to_client{user="hello"} 22758000640 (21.20 GB)
telemt_user_unique_ips_current{user="hello"} 24
```