# Server Metrics 2026-03-15 08:53:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 38323.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797654
telemt_connections_bad_total 34444
telemt_handshake_timeouts_total 5838
telemt_upstream_connect_attempt_total 7822
telemt_upstream_connect_success_total 7789
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 7822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5905
telemt_me_reconnect_success_total 5874
telemt_me_reader_eof_total 6216
telemt_me_idle_close_by_peer_total 6216
telemt_me_route_drop_no_conn_total 258339
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675911
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2098
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 1445
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 869
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5954
telemt_me_writer_restored_same_endpoint_total 5863
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 675905
telemt_user_connections_current{user="hello"} 2014
telemt_user_octets_from_client{user="hello"} 9046173628 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 254521353032 (237.04 GB)
telemt_user_unique_ips_current{user="hello"} 568
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 38324.5 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314920
telemt_connections_bad_total 18523
telemt_handshake_timeouts_total 12714
telemt_upstream_connect_attempt_total 10294
telemt_upstream_connect_success_total 10243
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 10294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8051
telemt_me_reconnect_success_total 8002
telemt_me_reader_eof_total 8473
telemt_me_idle_close_by_peer_total 8473
telemt_me_route_drop_no_conn_total 79213
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248953
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 930
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 8067
telemt_me_writer_restored_same_endpoint_total 7994
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 249228
telemt_user_connections_current{user="hello"} 736
telemt_user_octets_from_client{user="hello"} 3634693219 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 94622399312 (88.12 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 38324.6 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543553
telemt_connections_bad_total 17263
telemt_handshake_timeouts_total 48682
telemt_upstream_connect_attempt_total 8517
telemt_upstream_connect_success_total 8480
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 8517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 6595
telemt_me_reconnect_success_total 6552
telemt_me_reader_eof_total 6945
telemt_me_idle_close_by_peer_total 6945
telemt_me_route_drop_no_conn_total 151642
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 436396
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 909
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6633
telemt_me_writer_restored_same_endpoint_total 6533
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 435926
telemt_user_connections_current{user="hello"} 1189
telemt_user_octets_from_client{user="hello"} 6465315676 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 179196633952 (166.89 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 38324.4 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340306
telemt_connections_bad_total 50794
telemt_handshake_timeouts_total 22830
telemt_upstream_connect_attempt_total 12269
telemt_upstream_connect_success_total 11984
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 12269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 23891
telemt_me_reconnect_success_total 10064
telemt_me_reader_eof_total 10801
telemt_me_idle_close_by_peer_total 10801
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 90143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252930
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 608
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 10578
telemt_me_refill_failed_total 431
telemt_me_writer_restored_same_endpoint_total 10034
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 252933
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 2333542888 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 82502507576 (76.84 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 38325.7 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305007
telemt_connections_bad_total 3752
telemt_handshake_timeouts_total 3515
telemt_upstream_connect_attempt_total 8498
telemt_upstream_connect_success_total 8462
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 8498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 6579
telemt_me_reconnect_success_total 6549
telemt_me_reader_eof_total 6977
telemt_me_idle_close_by_peer_total 6977
telemt_me_route_drop_no_conn_total 85204
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263269
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1046
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 706
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 300
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6614
telemt_me_writer_restored_same_endpoint_total 6541
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 263274
telemt_user_connections_current{user="hello"} 757
telemt_user_octets_from_client{user="hello"} 2994338212 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 101234842556 (94.28 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 93
```