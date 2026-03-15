# Server Metrics 2026-03-15 14:30:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 58557.1 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1812924
telemt_connections_bad_total 99791
telemt_handshake_timeouts_total 20213
telemt_upstream_connect_attempt_total 11687
telemt_upstream_connect_success_total 11638
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13587
telemt_me_reconnect_success_total 8697
telemt_me_reader_eof_total 9303
telemt_me_idle_close_by_peer_total 9303
telemt_me_route_drop_no_conn_total 620201
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1533281
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5775
telemt_desync_full_logged_total 1614
telemt_desync_suppressed_total 4161
telemt_desync_frames_bucket_total{bucket="1_2"} 1450
telemt_desync_frames_bucket_total{bucket="3_10"} 2235
telemt_desync_frames_bucket_total{bucket="gt_10"} 2090
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8989
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8686
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 1532886
telemt_user_connections_current{user="hello"} 2267
telemt_user_octets_from_client{user="hello"} 21826433384 (20.33 GB)
telemt_user_octets_to_client{user="hello"} 604083965416 (562.60 GB)
telemt_user_unique_ips_current{user="hello"} 643
telemt_user_unique_ips_recent_window{user="hello"} 305
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 58557.7 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737070
telemt_connections_bad_total 39835
telemt_handshake_timeouts_total 57916
telemt_upstream_connect_attempt_total 14871
telemt_upstream_connect_success_total 14798
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 14871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11611
telemt_me_reconnect_success_total 11519
telemt_me_reader_eof_total 12176
telemt_me_idle_close_by_peer_total 12176
telemt_me_route_drop_no_conn_total 183171
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554160
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1989
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1301
telemt_desync_frames_bucket_total{bucket="1_2"} 739
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11662
telemt_me_writer_restored_same_endpoint_total 11507
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 554413
telemt_user_connections_current{user="hello"} 831
telemt_user_octets_from_client{user="hello"} 7761545907 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 207821792000 (193.55 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 58557.9 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1577692
telemt_connections_bad_total 45986
telemt_handshake_timeouts_total 161434
telemt_upstream_connect_attempt_total 12845
telemt_upstream_connect_success_total 12783
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 12844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 11081
telemt_me_reconnect_success_total 9827
telemt_me_reader_eof_total 10419
telemt_me_idle_close_by_peer_total 10419
telemt_me_route_drop_no_conn_total 431127
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 977829
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2462
telemt_desync_full_logged_total 906
telemt_desync_suppressed_total 1556
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 945
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9998
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9808
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 973912
telemt_user_connections_current{user="hello"} 1381
telemt_user_octets_from_client{user="hello"} 14086981256 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 351320088684 (327.19 GB)
telemt_user_unique_ips_current{user="hello"} 408
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 58557.8 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 761053
telemt_connections_bad_total 72377
telemt_handshake_timeouts_total 39983
telemt_upstream_connect_attempt_total 147226
telemt_upstream_connect_success_total 146748
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 147226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 50883
telemt_me_reconnect_success_total 11794
telemt_me_reader_eof_total 13347
telemt_me_idle_close_by_peer_total 13347
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 170859
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447063
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1173
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 476
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13126
telemt_me_refill_failed_total 1222
telemt_me_writer_restored_same_endpoint_total 11762
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1332
telemt_user_connections_total{user="hello"} 578953
telemt_user_connections_current{user="hello"} 945
telemt_user_octets_from_client{user="hello"} 10975811499 (10.22 GB)
telemt_user_octets_to_client{user="hello"} 196609622459 (183.11 GB)
telemt_user_msgs_from_client{user="hello"} 2625162
telemt_user_msgs_to_client{user="hello"} 9551017
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 58559.0 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 779182
telemt_connections_bad_total 9295
telemt_handshake_timeouts_total 16121
telemt_upstream_connect_attempt_total 12875
telemt_upstream_connect_success_total 12805
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 13546
telemt_me_reconnect_success_total 9871
telemt_me_reader_eof_total 10557
telemt_me_idle_close_by_peer_total 10557
telemt_me_route_drop_no_conn_total 193568
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 634492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2295
telemt_desync_full_logged_total 769
telemt_desync_suppressed_total 1526
telemt_desync_frames_bucket_total{bucket="1_2"} 686
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 717
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 10100
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9863
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 634536
telemt_user_connections_current{user="hello"} 956
telemt_user_octets_from_client{user="hello"} 7916341100 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 236873392412 (220.61 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 150
```