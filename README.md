# Server Metrics 2026-03-10 20:32:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21895.4 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 645960
telemt_connections_bad_total 8008
telemt_handshake_timeouts_total 7662
telemt_upstream_connect_attempt_total 4657
telemt_upstream_connect_success_total 4648
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 341
telemt_me_reconnect_attempts_total 15112
telemt_me_reconnect_success_total 3461
telemt_me_reader_eof_total 3868
telemt_me_idle_close_by_peer_total 3868
telemt_me_route_drop_no_conn_total 270699
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609082
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3156
telemt_desync_full_logged_total 855
telemt_desync_suppressed_total 2301
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3844
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 3455
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 383
telemt_user_connections_total{user="hello"} 608890
telemt_user_connections_current{user="hello"} 882
telemt_user_octets_from_client{user="hello"} 8730590896 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 181433876196 (168.97 GB)
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 21952.0 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284865
telemt_connections_bad_total 1828
telemt_handshake_timeouts_total 17062
telemt_upstream_connect_attempt_total 10340
telemt_upstream_connect_success_total 7493
telemt_upstream_connect_fail_total 2847
telemt_upstream_connect_attempts_per_request{bucket="1"} 10340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2847
telemt_me_keepalive_timeout_total 736
telemt_me_reconnect_attempts_total 4853
telemt_me_reconnect_success_total 4060
telemt_me_reader_eof_total 4250
telemt_me_idle_close_by_peer_total 4248
telemt_me_route_drop_no_conn_total 155854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238568
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1341
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 982
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 477
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4136
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 4039
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 240168
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2437781134 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 57037783562 (53.12 GB)
telemt_user_msgs_from_client{user="hello"} 5762
telemt_user_msgs_to_client{user="hello"} 6647
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 21951.8 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460520
telemt_connections_bad_total 2316
telemt_handshake_timeouts_total 32524
telemt_upstream_connect_attempt_total 6577
telemt_upstream_connect_success_total 6479
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 6577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 12609
telemt_me_reconnect_success_total 4258
telemt_me_reader_eof_total 4641
telemt_me_idle_close_by_peer_total 4641
telemt_me_route_drop_no_conn_total 159335
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1335
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 963
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4593
telemt_me_refill_failed_total 259
telemt_me_writer_restored_same_endpoint_total 4247
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 335
telemt_user_connections_total{user="hello"} 400847
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 5783299773 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 125305907789 (116.70 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 21952.4 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311781
telemt_connections_bad_total 21530
telemt_handshake_timeouts_total 26859
telemt_upstream_connect_attempt_total 6017
telemt_upstream_connect_success_total 6017
telemt_upstream_connect_attempts_per_request{bucket="1"} 6017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 5883
telemt_me_reconnect_success_total 4865
telemt_me_reader_eof_total 5102
telemt_me_idle_close_by_peer_total 5102
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 101093
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251407
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 394
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 171
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 4945
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 4852
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 251105
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 3812109016 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 78539778556 (73.15 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 21952.0 (6h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328177
telemt_connections_bad_total 987
telemt_handshake_timeouts_total 2067
telemt_upstream_connect_attempt_total 6968
telemt_upstream_connect_success_total 6941
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 6968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3229
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 9514
telemt_me_reconnect_success_total 5763
telemt_me_reader_eof_total 6025
telemt_me_idle_close_by_peer_total 6025
telemt_me_route_drop_no_conn_total 119198
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308790
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1790
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1121
telemt_desync_frames_bucket_total{bucket="1_2"} 694
telemt_desync_frames_bucket_total{bucket="3_10"} 753
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5963
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 5763
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 308694
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 5976229692 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 102954180824 (95.88 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 76
```