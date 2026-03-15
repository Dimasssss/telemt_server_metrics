# Server Metrics 2026-03-15 15:36:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 62542.5 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2031401
telemt_connections_bad_total 111186
telemt_handshake_timeouts_total 23480
telemt_upstream_connect_attempt_total 12509
telemt_upstream_connect_success_total 12454
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 12509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 14202
telemt_me_reconnect_success_total 9308
telemt_me_reader_eof_total 9946
telemt_me_idle_close_by_peer_total 9946
telemt_me_route_drop_no_conn_total 697534
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1715967
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6538
telemt_desync_full_logged_total 1805
telemt_desync_suppressed_total 4733
telemt_desync_frames_bucket_total{bucket="1_2"} 1614
telemt_desync_frames_bucket_total{bucket="3_10"} 2509
telemt_desync_frames_bucket_total{bucket="gt_10"} 2415
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9611
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 9297
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 1715479
telemt_user_connections_current{user="hello"} 2459
telemt_user_octets_from_client{user="hello"} 25265422344 (23.53 GB)
telemt_user_octets_to_client{user="hello"} 662003917592 (616.54 GB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 62543.4 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 808751
telemt_connections_bad_total 43198
telemt_handshake_timeouts_total 59237
telemt_upstream_connect_attempt_total 15778
telemt_upstream_connect_success_total 15702
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 15778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 12315
telemt_me_reconnect_success_total 12217
telemt_me_reader_eof_total 12910
telemt_me_idle_close_by_peer_total 12910
telemt_me_route_drop_no_conn_total 203096
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 615339
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2074
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1377
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12374
telemt_me_writer_restored_same_endpoint_total 12205
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 615581
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 8596483147 (8.01 GB)
telemt_user_octets_to_client{user="hello"} 232489603968 (216.52 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 62543.4 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1812496
telemt_connections_bad_total 47610
telemt_handshake_timeouts_total 180039
telemt_upstream_connect_attempt_total 13689
telemt_upstream_connect_success_total 13624
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 13689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11717
telemt_me_reconnect_success_total 10456
telemt_me_reader_eof_total 11081
telemt_me_idle_close_by_peer_total 11081
telemt_me_route_drop_no_conn_total 474197
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1091896
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2675
telemt_desync_full_logged_total 984
telemt_desync_suppressed_total 1691
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 1016
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10640
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 10437
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 1087872
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 15646836520 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 388934378632 (362.22 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 62543.2 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 855992
telemt_connections_bad_total 76122
telemt_handshake_timeouts_total 42334
telemt_upstream_connect_attempt_total 168058
telemt_upstream_connect_success_total 167549
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 168058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155023
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 52779
telemt_me_reconnect_success_total 12339
telemt_me_reader_eof_total 13952
telemt_me_idle_close_by_peer_total 13952
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 189653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505235
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1386
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 559
telemt_desync_frames_bucket_total{bucket="gt_10"} 461
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 13725
telemt_me_refill_failed_total 1265
telemt_me_writer_restored_same_endpoint_total 12305
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1386
telemt_user_connections_total{user="hello"} 656886
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 12975701910 (12.08 GB)
telemt_user_octets_to_client{user="hello"} 232767212361 (216.78 GB)
telemt_user_msgs_from_client{user="hello"} 3034166
telemt_user_msgs_to_client{user="hello"} 10923814
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 62544.1 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864245
telemt_connections_bad_total 9432
telemt_handshake_timeouts_total 18806
telemt_upstream_connect_attempt_total 13929
telemt_upstream_connect_success_total 13852
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 13929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 14389
telemt_me_reconnect_success_total 10707
telemt_me_reader_eof_total 11430
telemt_me_idle_close_by_peer_total 11430
telemt_me_route_drop_no_conn_total 215419
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710971
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2467
telemt_desync_full_logged_total 836
telemt_desync_suppressed_total 1631
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 948
telemt_desync_frames_bucket_total{bucket="gt_10"} 768
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 10947
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 10699
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 711011
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 8765002088 (8.16 GB)
telemt_user_octets_to_client{user="hello"} 256895246672 (239.25 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 147
```