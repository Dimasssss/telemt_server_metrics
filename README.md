# Server Metrics 2026-03-15 12:32:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 51505.6 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1451578
telemt_connections_bad_total 85222
telemt_handshake_timeouts_total 12344
telemt_upstream_connect_attempt_total 10284
telemt_upstream_connect_success_total 10236
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12515
telemt_me_reconnect_success_total 7636
telemt_me_reader_eof_total 8197
telemt_me_idle_close_by_peer_total 8197
telemt_me_route_drop_no_conn_total 485768
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218191
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4602
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 3307
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 1804
telemt_desync_frames_bucket_total{bucket="gt_10"} 1667
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7903
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7625
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 1217862
telemt_user_connections_current{user="hello"} 2249
telemt_user_octets_from_client{user="hello"} 17205168172 (16.02 GB)
telemt_user_octets_to_client{user="hello"} 486172182244 (452.78 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 328
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 51506.6 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580284
telemt_connections_bad_total 29516
telemt_handshake_timeouts_total 36601
telemt_upstream_connect_attempt_total 13371
telemt_upstream_connect_success_total 13304
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 13371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6006
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10446
telemt_me_reconnect_success_total 10373
telemt_me_reader_eof_total 10968
telemt_me_idle_close_by_peer_total 10968
telemt_me_route_drop_no_conn_total 146987
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448736
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 614
telemt_desync_suppressed_total 1139
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 642
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10488
telemt_me_writer_restored_same_endpoint_total 10361
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 449003
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 6345347815 (5.91 GB)
telemt_user_octets_to_client{user="hello"} 165363877744 (154.01 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 51506.3 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1166409
telemt_connections_bad_total 38021
telemt_handshake_timeouts_total 118919
telemt_upstream_connect_attempt_total 11416
telemt_upstream_connect_success_total 11360
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 9992
telemt_me_reconnect_success_total 8747
telemt_me_reader_eof_total 9282
telemt_me_idle_close_by_peer_total 9282
telemt_me_route_drop_no_conn_total 354905
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780801
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2009
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 816
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 8898
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8728
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 151
telemt_user_connections_total{user="hello"} 777293
telemt_user_connections_current{user="hello"} 1228
telemt_user_octets_from_client{user="hello"} 11390684932 (10.61 GB)
telemt_user_octets_to_client{user="hello"} 291565853112 (271.54 GB)
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 51506.3 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576076
telemt_connections_bad_total 66149
telemt_handshake_timeouts_total 32864
telemt_upstream_connect_attempt_total 14682
telemt_upstream_connect_success_total 14289
telemt_upstream_connect_fail_total 393
telemt_upstream_connect_attempts_per_request{bucket="1"} 14682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 393
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 40666
telemt_me_reconnect_success_total 11692
telemt_me_reader_eof_total 12931
telemt_me_idle_close_by_peer_total 12931
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 163654
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430694
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1135
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 304
telemt_desync_frames_bucket_total{bucket="3_10"} 464
telemt_desync_frames_bucket_total{bucket="gt_10"} 367
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12708
telemt_me_refill_failed_total 906
telemt_me_writer_restored_same_endpoint_total 11660
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1016
telemt_user_connections_total{user="hello"} 430555
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 8384984920 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 154073632348 (143.49 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 51507.4 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621517
telemt_connections_bad_total 7216
telemt_handshake_timeouts_total 13170
telemt_upstream_connect_attempt_total 11535
telemt_upstream_connect_success_total 11474
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 9917
telemt_me_reconnect_success_total 8875
telemt_me_reader_eof_total 9441
telemt_me_idle_close_by_peer_total 9441
telemt_me_route_drop_no_conn_total 155090
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 503712
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1962
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 572
telemt_desync_frames_bucket_total{bucket="3_10"} 776
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9012
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8867
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 503743
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 6528688040 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 180748583152 (168.34 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 115
```