# Server Metrics 2026-03-13 11:13:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 105276.1 (29h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3082372
telemt_connections_bad_total 36462
telemt_handshake_timeouts_total 54829
telemt_upstream_connect_attempt_total 20752
telemt_upstream_connect_success_total 20641
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 20752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1465
telemt_me_reconnect_attempts_total 25492
telemt_me_reconnect_success_total 15419
telemt_me_reader_eof_total 16584
telemt_me_idle_close_by_peer_total 16583
telemt_me_route_drop_no_conn_total 1140047
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2816407
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12182
telemt_desync_full_logged_total 3147
telemt_desync_suppressed_total 9035
telemt_desync_frames_bucket_total{bucket="1_2"} 3116
telemt_desync_frames_bucket_total{bucket="3_10"} 4564
telemt_desync_frames_bucket_total{bucket="gt_10"} 4502
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 15945
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 15406
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 2816349
telemt_user_connections_current{user="hello"} 1846
telemt_user_octets_from_client{user="hello"} 38927208304 (36.25 GB)
telemt_user_octets_to_client{user="hello"} 914082098564 (851.31 GB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 4939.8 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59746
telemt_connections_bad_total 4953
telemt_handshake_timeouts_total 1472
telemt_upstream_connect_attempt_total 1441
telemt_upstream_connect_success_total 1372
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 1441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 2286
telemt_me_reconnect_success_total 1064
telemt_me_reader_eof_total 1096
telemt_me_idle_close_by_peer_total 1096
telemt_me_route_drop_no_conn_total 21564
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51884
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1103
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1057
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 51877
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 545985096 (520.69 MB)
telemt_user_octets_to_client{user="hello"} 13187958624 (12.28 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 134896.6 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2371442
telemt_connections_bad_total 25262
telemt_handshake_timeouts_total 158914
telemt_upstream_connect_attempt_total 30661
telemt_upstream_connect_success_total 30650
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 30660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14478
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1929
telemt_me_reconnect_attempts_total 24896
telemt_me_reconnect_success_total 23601
telemt_me_reader_eof_total 25008
telemt_me_idle_close_by_peer_total 25007
telemt_me_route_drop_no_conn_total 782592
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1913080
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6348
telemt_desync_full_logged_total 2031
telemt_desync_suppressed_total 4317
telemt_desync_frames_bucket_total{bucket="1_2"} 1018
telemt_desync_frames_bucket_total{bucket="3_10"} 2315
telemt_desync_frames_bucket_total{bucket="gt_10"} 3015
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 23840
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 23560
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 239
telemt_user_connections_total{user="hello"} 1912504
telemt_user_connections_current{user="hello"} 1069
telemt_user_octets_from_client{user="hello"} 32711604876 (30.47 GB)
telemt_user_octets_to_client{user="hello"} 686404735701 (639.26 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 134897.2 (37h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1500976
telemt_connections_bad_total 15517
telemt_handshake_timeouts_total 96897
telemt_upstream_connect_attempt_total 43919
telemt_upstream_connect_success_total 41606
telemt_upstream_connect_fail_total 2176
telemt_upstream_connect_attempts_per_request{bucket="1"} 43645
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11557
telemt_me_reconnect_attempts_total 38002
telemt_me_reconnect_success_total 29047
telemt_me_reader_eof_total 31237
telemt_me_idle_close_by_peer_total 31230
telemt_me_route_drop_no_conn_total 533048
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1254775
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2329
telemt_desync_full_logged_total 778
telemt_desync_suppressed_total 1551
telemt_desync_frames_bucket_total{bucket="1_2"} 651
telemt_desync_frames_bucket_total{bucket="3_10"} 883
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 29539
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 29023
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 1259500
telemt_user_connections_current{user="hello"} 680
telemt_user_octets_from_client{user="hello"} 18980651809 (17.68 GB)
telemt_user_octets_to_client{user="hello"} 495993371478 (461.93 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 4332.4 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58625
telemt_connections_bad_total 24
telemt_handshake_timeouts_total 333
telemt_upstream_connect_attempt_total 1058
telemt_upstream_connect_success_total 1032
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 3375
telemt_me_reconnect_success_total 780
telemt_me_reader_eof_total 832
telemt_me_idle_close_by_peer_total 832
telemt_me_route_drop_no_conn_total 20998
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56199
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_me_writer_removed_unexpected_total 853
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 56191
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 595493848 (567.91 MB)
telemt_user_octets_to_client{user="hello"} 20382025928 (18.98 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 111
```