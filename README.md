# Server Metrics 2026-03-13 15:56:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 122273.4 (33h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3831608
telemt_connections_bad_total 37431
telemt_handshake_timeouts_total 88809
telemt_upstream_connect_attempt_total 23740
telemt_upstream_connect_success_total 23605
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2208
telemt_me_reconnect_attempts_total 27633
telemt_me_reconnect_success_total 17543
telemt_me_reader_eof_total 18853
telemt_me_idle_close_by_peer_total 18852
telemt_me_route_drop_no_conn_total 1419150
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3502724
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14042
telemt_desync_full_logged_total 3713
telemt_desync_suppressed_total 10329
telemt_desync_frames_bucket_total{bucket="1_2"} 3516
telemt_desync_frames_bucket_total{bucket="3_10"} 5309
telemt_desync_frames_bucket_total{bucket="gt_10"} 5217
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 18097
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17530
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3502524
telemt_user_connections_current{user="hello"} 1696
telemt_user_octets_from_client{user="hello"} 47588264472 (44.32 GB)
telemt_user_octets_to_client{user="hello"} 1098691589360 (1023.24 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21937.2 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317182
telemt_connections_bad_total 17646
telemt_handshake_timeouts_total 8732
telemt_upstream_connect_attempt_total 5112
telemt_upstream_connect_success_total 5026
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 5112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 6170
telemt_me_reconnect_success_total 3879
telemt_me_reader_eof_total 4123
telemt_me_idle_close_by_peer_total 4123
telemt_me_route_drop_no_conn_total 114147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282704
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4001
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3872
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 282734
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 2857293480 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 80114714060 (74.61 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 151893.9 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2828753
telemt_connections_bad_total 27805
telemt_handshake_timeouts_total 187940
telemt_upstream_connect_attempt_total 34035
telemt_upstream_connect_success_total 34025
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3284
telemt_me_reconnect_attempts_total 28693
telemt_me_reconnect_success_total 26143
telemt_me_reader_eof_total 27725
telemt_me_idle_close_by_peer_total 27724
telemt_me_route_drop_no_conn_total 955946
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2325273
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8230
telemt_desync_full_logged_total 2724
telemt_desync_suppressed_total 5506
telemt_desync_frames_bucket_total{bucket="1_2"} 1319
telemt_desync_frames_bucket_total{bucket="3_10"} 2990
telemt_desync_frames_bucket_total{bucket="gt_10"} 3921
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 26451
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26102
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 2324670
telemt_user_connections_current{user="hello"} 1104
telemt_user_octets_from_client{user="hello"} 38284860520 (35.66 GB)
telemt_user_octets_to_client{user="hello"} 811862251149 (756.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 151894.2 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1801527
telemt_connections_bad_total 18149
telemt_handshake_timeouts_total 143040
telemt_upstream_connect_attempt_total 47792
telemt_upstream_connect_success_total 45460
telemt_upstream_connect_fail_total 2195
telemt_upstream_connect_attempts_per_request{bucket="1"} 47518
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2194
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11884
telemt_me_reconnect_attempts_total 41030
telemt_me_reconnect_success_total 32057
telemt_me_reader_eof_total 34440
telemt_me_idle_close_by_peer_total 34433
telemt_me_route_drop_no_conn_total 645915
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1500345
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3010
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 2036
telemt_desync_frames_bucket_total{bucket="1_2"} 805
telemt_desync_frames_bucket_total{bucket="3_10"} 1243
telemt_desync_frames_bucket_total{bucket="gt_10"} 962
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 32585
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32033
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 1505054
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 23367721045 (21.76 GB)
telemt_user_octets_to_client{user="hello"} 575604794266 (536.07 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21330.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342967
telemt_connections_bad_total 4038
telemt_handshake_timeouts_total 3121
telemt_upstream_connect_attempt_total 4612
telemt_upstream_connect_success_total 4475
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 13958
telemt_me_reconnect_success_total 3384
telemt_me_reader_eof_total 3782
telemt_me_idle_close_by_peer_total 3782
telemt_me_route_drop_no_conn_total 135615
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321337
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1078
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 736
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3733
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3380
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 321312
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 3737800084 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 103303726328 (96.21 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 122
```