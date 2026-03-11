# Server Metrics 2026-03-11 13:45:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 83880.7 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1990513
telemt_connections_bad_total 27776
telemt_handshake_timeouts_total 51138
telemt_upstream_connect_attempt_total 17435
telemt_upstream_connect_success_total 17426
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 969
telemt_me_reconnect_attempts_total 26004
telemt_me_reconnect_success_total 13172
telemt_me_reader_eof_total 14225
telemt_me_idle_close_by_peer_total 14225
telemt_me_route_drop_no_conn_total 731990
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819248
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9600
telemt_desync_full_logged_total 2598
telemt_desync_suppressed_total 7002
telemt_desync_frames_bucket_total{bucket="1_2"} 2368
telemt_desync_frames_bucket_total{bucket="3_10"} 3710
telemt_desync_frames_bucket_total{bucket="gt_10"} 3522
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13712
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13166
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 540
telemt_user_connections_total{user="hello"} 1817760
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 24238266080 (22.57 GB)
telemt_user_octets_to_client{user="hello"} 517775265504 (482.22 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 83937.6 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 752707
telemt_connections_bad_total 13080
telemt_handshake_timeouts_total 51199
telemt_upstream_connect_attempt_total 26971
telemt_upstream_connect_success_total 24023
telemt_upstream_connect_fail_total 2948
telemt_upstream_connect_attempts_per_request{bucket="1"} 26971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10694
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2948
telemt_me_keepalive_timeout_total 2463
telemt_me_reconnect_attempts_total 17717
telemt_me_reconnect_success_total 16852
telemt_me_reader_eof_total 17819
telemt_me_idle_close_by_peer_total 17816
telemt_me_route_drop_no_conn_total 294263
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2768
telemt_desync_full_logged_total 877
telemt_desync_suppressed_total 1891
telemt_desync_frames_bucket_total{bucket="1_2"} 865
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 895
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17063
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 16829
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 638142
telemt_user_connections_current{user="hello"} 520
telemt_user_octets_from_client{user="hello"} 6832088758 (6.36 GB)
telemt_user_octets_to_client{user="hello"} 181131172200 (168.69 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 83937.2 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1299395
telemt_connections_bad_total 8305
telemt_handshake_timeouts_total 119060
telemt_upstream_connect_attempt_total 22318
telemt_upstream_connect_success_total 22047
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 900
telemt_me_reconnect_attempts_total 32836
telemt_me_reconnect_success_total 16729
telemt_me_reader_eof_total 17996
telemt_me_idle_close_by_peer_total 17996
telemt_me_route_drop_no_conn_total 451950
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123462
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2989
telemt_desync_full_logged_total 885
telemt_desync_suppressed_total 2104
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17454
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16718
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 1123830
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 13250699929 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 335720292625 (312.66 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 246
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 83937.9 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 934607
telemt_connections_bad_total 77220
telemt_handshake_timeouts_total 88686
telemt_upstream_connect_attempt_total 22827
telemt_upstream_connect_success_total 22827
telemt_upstream_connect_attempts_per_request{bucket="1"} 22827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 939
telemt_me_reconnect_attempts_total 19688
telemt_me_reconnect_success_total 18618
telemt_me_reader_eof_total 19742
telemt_me_idle_close_by_peer_total 19741
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 301630
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 743241
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1599
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 975
telemt_desync_frames_bucket_total{bucket="1_2"} 577
telemt_desync_frames_bucket_total{bucket="3_10"} 562
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18847
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18590
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 742601
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 8604876400 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 215373287360 (200.58 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 83937.3 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1021563
telemt_connections_bad_total 6821
telemt_handshake_timeouts_total 9326
telemt_upstream_connect_attempt_total 22864
telemt_upstream_connect_success_total 22765
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 22864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 978
telemt_me_reconnect_attempts_total 22502
telemt_me_reconnect_success_total 18428
telemt_me_reader_eof_total 19449
telemt_me_idle_close_by_peer_total 19449
telemt_me_route_drop_no_conn_total 361333
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 927914
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3710
telemt_desync_full_logged_total 1367
telemt_desync_suppressed_total 2343
telemt_desync_frames_bucket_total{bucket="1_2"} 1300
telemt_desync_frames_bucket_total{bucket="3_10"} 1401
telemt_desync_frames_bucket_total{bucket="gt_10"} 1009
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18791
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18428
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 363
telemt_user_connections_total{user="hello"} 927656
telemt_user_connections_current{user="hello"} 676
telemt_user_octets_from_client{user="hello"} 13564469771 (12.63 GB)
telemt_user_octets_to_client{user="hello"} 330030409642 (307.36 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 114
```