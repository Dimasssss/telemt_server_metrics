# Server Metrics 2026-03-14 14:40:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.17

telemt_uptime_seconds 4998.3 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201063
telemt_connections_bad_total 4241
telemt_handshake_timeouts_total 2822
telemt_upstream_connect_attempt_total 1012
telemt_upstream_connect_success_total 1006
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 1484
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 724
telemt_me_idle_close_by_peer_total 724
telemt_me_route_drop_no_conn_total 77713
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185193
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 375
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 243
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 738
telemt_me_refill_failed_total 24
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 484
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 185187
telemt_user_connections_current{user="hello"} 1766
telemt_user_octets_from_client{user="hello"} 3217130936 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 51722840060 (48.17 GB)
telemt_user_unique_ips_current{user="hello"} 496
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## server2

```
telemt 3.3.17

telemt_uptime_seconds 5003.6 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79297
telemt_connections_bad_total 5897
telemt_handshake_timeouts_total 2962
telemt_upstream_connect_attempt_total 1071
telemt_upstream_connect_success_total 1065
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 779
telemt_me_reconnect_success_total 763
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 25022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64409
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 419
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 119
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_restored_same_endpoint_total 752
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 64368
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 882235332 (841.37 MB)
telemt_user_octets_to_client{user="hello"} 30561414672 (28.46 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.17

telemt_uptime_seconds 4866.6 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141389
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 20806
telemt_upstream_connect_attempt_total 1068
telemt_upstream_connect_success_total 1064
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 774
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 748
telemt_me_idle_close_by_peer_total 748
telemt_me_route_drop_no_conn_total 41015
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112892
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 30
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 219
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 162
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 758
telemt_me_writer_restored_same_endpoint_total 732
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 1168
telemt_user_connections_total{user="hello"} 112857
telemt_user_connections_current{user="hello"} 1064
telemt_user_octets_from_client{user="hello"} 1688601572 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 33065607384 (30.79 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server4

```
telemt 3.3.17

telemt_uptime_seconds 4720.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76331
telemt_connections_bad_total 20627
telemt_handshake_timeouts_total 10885
telemt_upstream_connect_attempt_total 1306
telemt_upstream_connect_success_total 1306
telemt_upstream_connect_attempts_per_request{bucket="1"} 1306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1019
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 17392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43945
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1010
telemt_me_writer_restored_same_endpoint_total 1011
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 20
telemt_user_connections_total{user="hello"} 43913
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 928409036 (885.40 MB)
telemt_user_octets_to_client{user="hello"} 12162039768 (11.33 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server5

```
telemt 3.3.17

telemt_uptime_seconds 5016.4 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79897
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 1210
telemt_upstream_connect_attempt_total 1179
telemt_upstream_connect_success_total 1155
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1511
telemt_me_reconnect_success_total 861
telemt_me_reader_eof_total 887
telemt_me_idle_close_by_peer_total 887
telemt_me_route_drop_no_conn_total 27364
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 277
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 899
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 843
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 73178
telemt_user_connections_current{user="hello"} 750
telemt_user_octets_from_client{user="hello"} 1091729308 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 25405970144 (23.66 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 99
```