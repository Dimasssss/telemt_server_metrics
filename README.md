# Server Metrics 2026-03-15 03:52:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 20286.6 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248925
telemt_connections_bad_total 3442
telemt_handshake_timeouts_total 1232
telemt_upstream_connect_attempt_total 4329
telemt_upstream_connect_success_total 4312
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 4329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 3301
telemt_me_reconnect_success_total 3285
telemt_me_reader_eof_total 3465
telemt_me_idle_close_by_peer_total 3465
telemt_me_route_drop_no_conn_total 76819
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220236
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 576
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3323
telemt_me_writer_restored_same_endpoint_total 3274
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 220211
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 2363870140 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 78472347792 (73.08 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 20287.2 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99609
telemt_connections_bad_total 16634
telemt_handshake_timeouts_total 3840
telemt_upstream_connect_attempt_total 6067
telemt_upstream_connect_success_total 6042
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 6067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 4726
telemt_me_reconnect_success_total 4703
telemt_me_reader_eof_total 4963
telemt_me_idle_close_by_peer_total 4963
telemt_me_route_drop_no_conn_total 19866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76659
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4697
telemt_me_writer_restored_same_endpoint_total 4695
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 76955
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 1679650403 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 22723913556 (21.16 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 20287.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172702
telemt_connections_bad_total 3474
telemt_handshake_timeouts_total 17064
telemt_upstream_connect_attempt_total 4726
telemt_upstream_connect_success_total 4707
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 4726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 3692
telemt_me_reconnect_success_total 3674
telemt_me_reader_eof_total 3880
telemt_me_idle_close_by_peer_total 3880
telemt_me_route_drop_no_conn_total 37365
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149087
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 282
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3712
telemt_me_writer_restored_same_endpoint_total 3655
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 148984
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 1256795436 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 45716352664 (42.58 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 20287.3 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137513
telemt_connections_bad_total 31611
telemt_handshake_timeouts_total 5726
telemt_upstream_connect_attempt_total 7055
telemt_upstream_connect_success_total 6913
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 7055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9433
telemt_me_reconnect_success_total 5879
telemt_me_reader_eof_total 6186
telemt_me_idle_close_by_peer_total 6186
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 27641
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98212
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 110
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 6043
telemt_me_refill_failed_total 110
telemt_me_writer_restored_same_endpoint_total 5859
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 98217
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 754659004 (719.70 MB)
telemt_user_octets_to_client{user="hello"} 26715762152 (24.88 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 20288.1 (5h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83993
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 1035
telemt_upstream_connect_attempt_total 4704
telemt_upstream_connect_success_total 4683
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 4704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 3667
telemt_me_reconnect_success_total 3653
telemt_me_reader_eof_total 3892
telemt_me_idle_close_by_peer_total 3892
telemt_me_route_drop_no_conn_total 21903
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80336
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3686
telemt_me_writer_restored_same_endpoint_total 3645
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 80334
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 683960216 (652.28 MB)
telemt_user_octets_to_client{user="hello"} 25650536656 (23.89 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 34
```