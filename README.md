# Server Metrics 2026-03-11 14:00:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 84800.0 (23h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022552
telemt_connections_bad_total 28335
telemt_handshake_timeouts_total 51926
telemt_upstream_connect_attempt_total 17735
telemt_upstream_connect_success_total 17726
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 17735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 26259
telemt_me_reconnect_success_total 13425
telemt_me_reader_eof_total 14482
telemt_me_idle_close_by_peer_total 14482
telemt_me_route_drop_no_conn_total 743770
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1849181
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9701
telemt_desync_full_logged_total 2630
telemt_desync_suppressed_total 7071
telemt_desync_frames_bucket_total{bucket="1_2"} 2392
telemt_desync_frames_bucket_total{bucket="3_10"} 3752
telemt_desync_frames_bucket_total{bucket="gt_10"} 3557
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 13968
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 13419
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 543
telemt_user_connections_total{user="hello"} 1847693
telemt_user_connections_current{user="hello"} 1519
telemt_user_octets_from_client{user="hello"} 24760040140 (23.06 GB)
telemt_user_octets_to_client{user="hello"} 525696007500 (489.59 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 84856.7 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 762733
telemt_connections_bad_total 13096
telemt_handshake_timeouts_total 51616
telemt_upstream_connect_attempt_total 27308
telemt_upstream_connect_success_total 24359
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2509
telemt_me_reconnect_attempts_total 19224
telemt_me_reconnect_success_total 17141
telemt_me_reader_eof_total 18148
telemt_me_idle_close_by_peer_total 18145
telemt_me_route_drop_no_conn_total 298050
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645034
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2800
telemt_desync_full_logged_total 887
telemt_desync_suppressed_total 1913
telemt_desync_frames_bucket_total{bucket="1_2"} 872
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 909
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17393
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17118
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 647521
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 6886405838 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 183493383504 (170.89 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 84856.7 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1318577
telemt_connections_bad_total 8358
telemt_handshake_timeouts_total 120061
telemt_upstream_connect_attempt_total 22568
telemt_upstream_connect_success_total 22297
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 22568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 902
telemt_me_reconnect_attempts_total 33041
telemt_me_reconnect_success_total 16932
telemt_me_reader_eof_total 18203
telemt_me_idle_close_by_peer_total 18203
telemt_me_route_drop_no_conn_total 472746
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1140997
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3031
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 2133
telemt_desync_frames_bucket_total{bucket="1_2"} 729
telemt_desync_frames_bucket_total{bucket="3_10"} 1144
telemt_desync_frames_bucket_total{bucket="gt_10"} 1158
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 17661
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 16921
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 729
telemt_user_connections_total{user="hello"} 1140884
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 13728757201 (12.79 GB)
telemt_user_octets_to_client{user="hello"} 340634898417 (317.24 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 84857.1 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 946942
telemt_connections_bad_total 77222
telemt_handshake_timeouts_total 89686
telemt_upstream_connect_attempt_total 23084
telemt_upstream_connect_success_total 23084
telemt_upstream_connect_attempts_per_request{bucket="1"} 23084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 950
telemt_me_reconnect_attempts_total 19902
telemt_me_reconnect_success_total 18831
telemt_me_reader_eof_total 19973
telemt_me_idle_close_by_peer_total 19972
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 306323
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 754321
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1607
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 979
telemt_desync_frames_bucket_total{bucket="1_2"} 581
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19063
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 18803
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 753671
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 8709678724 (8.11 GB)
telemt_user_octets_to_client{user="hello"} 218766848824 (203.74 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 84856.8 (23h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1037563
telemt_connections_bad_total 6824
telemt_handshake_timeouts_total 9442
telemt_upstream_connect_attempt_total 23032
telemt_upstream_connect_success_total 22932
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 23032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_timeout_total 980
telemt_me_reconnect_attempts_total 22625
telemt_me_reconnect_success_total 18551
telemt_me_reader_eof_total 19580
telemt_me_idle_close_by_peer_total 19580
telemt_me_route_drop_no_conn_total 367558
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 942518
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3735
telemt_desync_full_logged_total 1378
telemt_desync_suppressed_total 2357
telemt_desync_frames_bucket_total{bucket="1_2"} 1313
telemt_desync_frames_bucket_total{bucket="3_10"} 1405
telemt_desync_frames_bucket_total{bucket="gt_10"} 1017
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18916
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 18551
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 365
telemt_user_connections_total{user="hello"} 942255
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 13722615083 (12.78 GB)
telemt_user_octets_to_client{user="hello"} 334275023726 (311.32 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 132
```