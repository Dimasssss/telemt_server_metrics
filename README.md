# Server Metrics 2026-03-10 18:44:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 15457.9 (4h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504541
telemt_connections_bad_total 7985
telemt_handshake_timeouts_total 2430
telemt_upstream_connect_attempt_total 3120
telemt_upstream_connect_success_total 3111
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 288
telemt_me_reconnect_attempts_total 12709
telemt_me_reconnect_success_total 2251
telemt_me_reader_eof_total 2568
telemt_me_idle_close_by_peer_total 2568
telemt_me_route_drop_no_conn_total 212244
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475937
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2454
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1783
telemt_desync_frames_bucket_total{bucket="1_2"} 654
telemt_desync_frames_bucket_total{bucket="3_10"} 940
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2586
telemt_me_refill_failed_total 326
telemt_me_writer_restored_same_endpoint_total 2245
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 475851
telemt_user_connections_current{user="hello"} 1233
telemt_user_octets_from_client{user="hello"} 6889322796 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 136982055916 (127.57 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 15514.7 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221568
telemt_connections_bad_total 1812
telemt_handshake_timeouts_total 16241
telemt_upstream_connect_attempt_total 8236
telemt_upstream_connect_success_total 5493
telemt_upstream_connect_fail_total 2743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1871
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2743
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 2749
telemt_me_reconnect_success_total 2669
telemt_me_reader_eof_total 2775
telemt_me_idle_close_by_peer_total 2773
telemt_me_route_drop_no_conn_total 125761
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 707
telemt_desync_full_logged_total 219
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2701
telemt_me_writer_restored_same_endpoint_total 2648
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 187705
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 2051922198 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 44520422142 (41.46 GB)
telemt_user_msgs_from_client{user="hello"} 5318
telemt_user_msgs_to_client{user="hello"} 5495
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 15514.6 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366849
telemt_connections_bad_total 1071
telemt_handshake_timeouts_total 31823
telemt_upstream_connect_attempt_total 4972
telemt_upstream_connect_success_total 4893
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 6414
telemt_me_reconnect_success_total 3001
telemt_me_reader_eof_total 3203
telemt_me_idle_close_by_peer_total 3203
telemt_me_route_drop_no_conn_total 122369
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309716
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 942
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 673
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 391
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3160
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 2990
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 310673
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 4274994717 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 98808701869 (92.02 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 15515.0 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238416
telemt_connections_bad_total 15227
telemt_handshake_timeouts_total 21480
telemt_upstream_connect_attempt_total 4068
telemt_upstream_connect_success_total 4068
telemt_upstream_connect_attempts_per_request{bucket="1"} 4068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 3249
telemt_me_reconnect_success_total 3229
telemt_me_reader_eof_total 3346
telemt_me_idle_close_by_peer_total 3346
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 78585
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191718
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 528
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3258
telemt_me_writer_restored_same_endpoint_total 3217
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 191511
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 2858992096 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 54259971356 (50.53 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15514.8 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252694
telemt_connections_bad_total 802
telemt_handshake_timeouts_total 1768
telemt_upstream_connect_attempt_total 4681
telemt_upstream_connect_success_total 4665
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 4681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3839
telemt_me_reconnect_success_total 3809
telemt_me_reader_eof_total 3925
telemt_me_idle_close_by_peer_total 3925
telemt_me_route_drop_no_conn_total 93726
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238336
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1348
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 868
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 3858
telemt_me_writer_restored_same_endpoint_total 3809
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 238268
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 5067258296 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 75266292936 (70.10 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 70
```