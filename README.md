# Server Metrics 2026-03-10 23:45:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 33495.6 (9h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767819
telemt_connections_bad_total 8949
telemt_handshake_timeouts_total 8533
telemt_upstream_connect_attempt_total 7272
telemt_upstream_connect_success_total 7263
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 7272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 459
telemt_me_reconnect_attempts_total 17162
telemt_me_reconnect_success_total 5500
telemt_me_reader_eof_total 6049
telemt_me_idle_close_by_peer_total 6049
telemt_me_route_drop_no_conn_total 317586
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727016
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3522
telemt_desync_full_logged_total 983
telemt_desync_suppressed_total 2539
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 1313
telemt_desync_frames_bucket_total{bucket="gt_10"} 1190
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 5910
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 5494
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 726805
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 10136986468 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 217228427664 (202.31 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33552.1 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332573
telemt_connections_bad_total 2381
telemt_handshake_timeouts_total 17612
telemt_upstream_connect_attempt_total 14127
telemt_upstream_connect_success_total 11251
telemt_upstream_connect_fail_total 2876
telemt_upstream_connect_attempts_per_request{bucket="1"} 14127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4207
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2876
telemt_me_keepalive_timeout_total 1685
telemt_me_reconnect_attempts_total 7384
telemt_me_reconnect_success_total 6573
telemt_me_reader_eof_total 6927
telemt_me_idle_close_by_peer_total 6925
telemt_me_route_drop_no_conn_total 170357
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282244
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 605
telemt_desync_frames_bucket_total{bucket="gt_10"} 582
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6667
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 6552
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 284513
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2771956126 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 69038784308 (64.30 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33552.0 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 551479
telemt_connections_bad_total 3688
telemt_handshake_timeouts_total 33987
telemt_upstream_connect_attempt_total 9102
telemt_upstream_connect_success_total 8975
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 9102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 493
telemt_me_reconnect_attempts_total 17229
telemt_me_reconnect_success_total 6172
telemt_me_reader_eof_total 6769
telemt_me_idle_close_by_peer_total 6769
telemt_me_route_drop_no_conn_total 190801
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485339
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1520
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6610
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 6161
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 438
telemt_user_connections_total{user="hello"} 486264
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 6757906517 (6.29 GB)
telemt_user_octets_to_client{user="hello"} 152168594837 (141.72 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33552.5 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396807
telemt_connections_bad_total 32076
telemt_handshake_timeouts_total 36562
telemt_upstream_connect_attempt_total 9397
telemt_upstream_connect_success_total 9397
telemt_upstream_connect_attempts_per_request{bucket="1"} 9397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4112
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 8695
telemt_me_reconnect_success_total 7667
telemt_me_reader_eof_total 8086
telemt_me_idle_close_by_peer_total 8086
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 124596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315202
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7780
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 7652
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 314877
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 4098754764 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 88922920724 (82.82 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33551.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420166
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 2688
telemt_upstream_connect_attempt_total 10250
telemt_upstream_connect_success_total 10210
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 10250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 492
telemt_me_reconnect_attempts_total 12208
telemt_me_reconnect_success_total 8446
telemt_me_reader_eof_total 8873
telemt_me_idle_close_by_peer_total 8873
telemt_me_route_drop_no_conn_total 142897
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389388
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2240
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1378
telemt_desync_frames_bucket_total{bucket="1_2"} 825
telemt_desync_frames_bucket_total{bucket="3_10"} 961
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 8675
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 8446
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 389167
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 6531902780 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 142840485816 (133.03 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 34
```