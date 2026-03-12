# Server Metrics 2026-03-12 14:39:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 31276.5 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113407
telemt_connections_bad_total 15113
telemt_handshake_timeouts_total 11743
telemt_upstream_connect_attempt_total 6172
telemt_upstream_connect_success_total 6138
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 6172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 406
telemt_me_reconnect_attempts_total 8449
telemt_me_reconnect_success_total 4547
telemt_me_reader_eof_total 4851
telemt_me_idle_close_by_peer_total 4850
telemt_me_route_drop_no_conn_total 395482
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1051375
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5674
telemt_desync_full_logged_total 1423
telemt_desync_suppressed_total 4251
telemt_desync_frames_bucket_total{bucket="1_2"} 1451
telemt_desync_frames_bucket_total{bucket="3_10"} 2045
telemt_desync_frames_bucket_total{bucket="gt_10"} 2178
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4721
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 4534
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1051108
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 16754236620 (15.60 GB)
telemt_user_octets_to_client{user="hello"} 305980316828 (284.97 GB)
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 60897.1 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516912
telemt_connections_bad_total 5396
telemt_handshake_timeouts_total 26301
telemt_upstream_connect_attempt_total 14539
telemt_upstream_connect_success_total 14532
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 14539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1161
telemt_me_reconnect_attempts_total 11375
telemt_me_reconnect_success_total 11311
telemt_me_reader_eof_total 12020
telemt_me_idle_close_by_peer_total 12020
telemt_me_route_drop_no_conn_total 150034
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460436
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1724
telemt_desync_full_logged_total 545
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 730
telemt_desync_frames_bucket_total{bucket="3_10"} 567
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11414
telemt_me_writer_restored_same_endpoint_total 11302
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 460935
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 7109204835 (6.62 GB)
telemt_user_octets_to_client{user="hello"} 163450398482 (152.23 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 60896.9 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1111447
telemt_connections_bad_total 6017
telemt_handshake_timeouts_total 79647
telemt_upstream_connect_attempt_total 14642
telemt_upstream_connect_success_total 14637
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 946
telemt_me_reconnect_attempts_total 12459
telemt_me_reconnect_success_total 11239
telemt_me_reader_eof_total 11855
telemt_me_idle_close_by_peer_total 11855
telemt_me_route_drop_no_conn_total 292531
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 803437
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3361
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2333
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 1222
telemt_desync_frames_bucket_total{bucket="gt_10"} 1645
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 11318
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11198
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 803625
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 10547459580 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 255582776397 (238.03 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 60897.4 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 651450
telemt_connections_bad_total 7691
telemt_handshake_timeouts_total 56712
telemt_upstream_connect_attempt_total 16189
telemt_upstream_connect_success_total 16124
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1346
telemt_me_reconnect_attempts_total 14320
telemt_me_reconnect_success_total 13084
telemt_me_reader_eof_total 13855
telemt_me_idle_close_by_peer_total 13855
telemt_me_route_drop_no_conn_total 219743
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554187
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1098
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 716
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 450
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13221
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 13063
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 553690
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 6699295876 (6.24 GB)
telemt_user_octets_to_client{user="hello"} 223327570008 (207.99 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 60897.4 (16h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 733625
telemt_connections_bad_total 5022
telemt_handshake_timeouts_total 5875
telemt_upstream_connect_attempt_total 19008
telemt_upstream_connect_success_total 18779
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 19008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 1075
telemt_me_reconnect_attempts_total 22968
telemt_me_reconnect_success_total 15739
telemt_me_reader_eof_total 16499
telemt_me_idle_close_by_peer_total 16499
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 253009
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678965
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2756
telemt_desync_full_logged_total 929
telemt_desync_suppressed_total 1827
telemt_desync_frames_bucket_total{bucket="1_2"} 787
telemt_desync_frames_bucket_total{bucket="3_10"} 956
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 16127
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 15705
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 678865
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 7909972244 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 184697201424 (172.01 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 107
```