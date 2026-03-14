# Server Metrics 2026-03-14 23:22:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 4100.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62101
telemt_connections_bad_total 638
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 881
telemt_upstream_connect_success_total 879
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 644
telemt_me_reconnect_success_total 642
telemt_me_reader_eof_total 655
telemt_me_idle_close_by_peer_total 655
telemt_me_route_drop_no_conn_total 19937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56903
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 195
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 149
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_restored_same_endpoint_total 631
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 56896
telemt_user_connections_current{user="hello"} 738
telemt_user_octets_from_client{user="hello"} 756097732 (721.07 MB)
telemt_user_octets_to_client{user="hello"} 22841801784 (21.27 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 4101.2 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25509
telemt_connections_bad_total 3840
telemt_handshake_timeouts_total 1710
telemt_upstream_connect_attempt_total 1513
telemt_upstream_connect_success_total 1502
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 962
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 4863
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18960
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 912
telemt_me_writer_restored_same_endpoint_total 944
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_user_connections_total{user="hello"} 19256
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 1230123035 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 4901343136 (4.56 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 4101.5 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40266
telemt_connections_bad_total 978
telemt_handshake_timeouts_total 2365
telemt_upstream_connect_attempt_total 866
telemt_upstream_connect_success_total 859
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 10249
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36395
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 622
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 36318
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 590352852 (563.00 MB)
telemt_user_octets_to_client{user="hello"} 12794756396 (11.92 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 4101.4 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27640
telemt_connections_bad_total 3553
telemt_handshake_timeouts_total 766
telemt_upstream_connect_attempt_total 1294
telemt_upstream_connect_success_total 1245
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1021
telemt_me_reconnect_success_total 1000
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 5964
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22886
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_restored_same_endpoint_total 987
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 22888
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 187141636 (178.47 MB)
telemt_user_octets_to_client{user="hello"} 5932333216 (5.52 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 4102.1 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22180
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 512
telemt_upstream_connect_attempt_total 798
telemt_upstream_connect_success_total 794
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 558
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 564
telemt_me_idle_close_by_peer_total 564
telemt_me_route_drop_no_conn_total 4968
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21116
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 562
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 21116
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 172863968 (164.86 MB)
telemt_user_octets_to_client{user="hello"} 12053089180 (11.23 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 32
```