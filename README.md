# Server Metrics 2026-03-14 05:59:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 172827.2 (48h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4870914
telemt_connections_bad_total 40024
telemt_handshake_timeouts_total 112532
telemt_upstream_connect_attempt_total 36319
telemt_upstream_connect_success_total 36082
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7311
telemt_me_reconnect_attempts_total 35315
telemt_me_reconnect_success_total 25169
telemt_me_reader_eof_total 27013
telemt_me_idle_close_by_peer_total 27012
telemt_me_route_drop_no_conn_total 1844452
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4469355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17167
telemt_desync_full_logged_total 4635
telemt_desync_suppressed_total 12532
telemt_desync_frames_bucket_total{bucket="1_2"} 4280
telemt_desync_frames_bucket_total{bucket="3_10"} 6563
telemt_desync_frames_bucket_total{bucket="gt_10"} 6324
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25847
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25156
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 678
telemt_user_connections_total{user="hello"} 4470893
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 65345685604 (60.86 GB)
telemt_user_octets_to_client{user="hello"} 1410010627881 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72491.1 (20h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789812
telemt_connections_bad_total 53076
telemt_handshake_timeouts_total 14574
telemt_upstream_connect_attempt_total 19802
telemt_upstream_connect_success_total 19532
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 19802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 2116
telemt_me_reconnect_attempts_total 17351
telemt_me_reconnect_success_total 13891
telemt_me_reader_eof_total 14766
telemt_me_idle_close_by_peer_total 14765
telemt_me_route_drop_no_conn_total 257319
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 624131
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1856
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1300
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 831
telemt_desync_frames_bucket_total{bucket="gt_10"} 639
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14190
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13883
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 626083
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 6631164373 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 210812520216 (196.33 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 202447.8 (56h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3499143
telemt_connections_bad_total 38134
telemt_handshake_timeouts_total 231066
telemt_upstream_connect_attempt_total 45730
telemt_upstream_connect_success_total 45709
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10632
telemt_me_reconnect_attempts_total 40319
telemt_me_reconnect_success_total 35347
telemt_me_reader_eof_total 37552
telemt_me_idle_close_by_peer_total 37551
telemt_me_route_drop_no_conn_total 1196277
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2917209
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9630
telemt_desync_full_logged_total 3236
telemt_desync_suppressed_total 6394
telemt_desync_frames_bucket_total{bucket="1_2"} 1675
telemt_desync_frames_bucket_total{bucket="3_10"} 3479
telemt_desync_frames_bucket_total{bucket="gt_10"} 4476
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 35839
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35306
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 2916419
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 47556313040 (44.29 GB)
telemt_user_octets_to_client{user="hello"} 1043473670369 (971.81 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 202450.4 (56h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2341956
telemt_connections_bad_total 23173
telemt_handshake_timeouts_total 271023
telemt_upstream_connect_attempt_total 63172
telemt_upstream_connect_success_total 60690
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62898
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20483
telemt_me_reconnect_attempts_total 52657
telemt_me_reconnect_success_total 43615
telemt_me_reader_eof_total 46761
telemt_me_idle_close_by_peer_total 46754
telemt_me_route_drop_no_conn_total 791649
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1852399
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3889
telemt_desync_full_logged_total 1256
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1047
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 44275
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43591
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1858397
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 28122753023 (26.19 GB)
telemt_user_octets_to_client{user="hello"} 682451760686 (635.58 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71884.3 (19h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 765742
telemt_connections_bad_total 8030
telemt_handshake_timeouts_total 9032
telemt_upstream_connect_attempt_total 18515
telemt_upstream_connect_success_total 18024
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 18515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 1563
telemt_me_reconnect_attempts_total 57003
telemt_me_reconnect_success_total 14450
telemt_me_reader_eof_total 16135
telemt_me_idle_close_by_peer_total 16134
telemt_me_route_drop_no_conn_total 294156
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715250
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15905
telemt_me_refill_failed_total 1325
telemt_me_writer_restored_same_endpoint_total 14445
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1455
telemt_user_connections_total{user="hello"} 715118
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 12763392588 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 238333751364 (221.97 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 63
```