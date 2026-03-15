# Server Metrics 2026-03-15 18:25:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 72659.2 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2604659
telemt_connections_bad_total 151765
telemt_handshake_timeouts_total 34275
telemt_upstream_connect_attempt_total 14012
telemt_upstream_connect_success_total 13952
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 14012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 15223
telemt_me_reconnect_success_total 10324
telemt_me_reader_eof_total 11036
telemt_me_idle_close_by_peer_total 11036
telemt_me_route_drop_no_conn_total 903731
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2176364
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8436
telemt_desync_full_logged_total 2309
telemt_desync_suppressed_total 6127
telemt_desync_frames_bucket_total{bucket="1_2"} 2077
telemt_desync_frames_bucket_total{bucket="3_10"} 3219
telemt_desync_frames_bucket_total{bucket="gt_10"} 3140
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10651
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 10313
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 2175830
telemt_user_connections_current{user="hello"} 2426
telemt_user_octets_from_client{user="hello"} 32837926984 (30.58 GB)
telemt_user_octets_to_client{user="hello"} 830144407004 (773.13 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 266
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 72660.1 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1007868
telemt_connections_bad_total 57900
telemt_handshake_timeouts_total 64198
telemt_upstream_connect_attempt_total 17968
telemt_upstream_connect_success_total 17871
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 40
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 15096
telemt_me_reconnect_success_total 13883
telemt_me_reader_eof_total 14692
telemt_me_idle_close_by_peer_total 14692
telemt_me_route_drop_no_conn_total 261817
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779535
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2240
telemt_desync_full_logged_total 764
telemt_desync_suppressed_total 1476
telemt_desync_frames_bucket_total{bucket="1_2"} 782
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 612
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14103
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 13871
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 779766
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 11272847191 (10.50 GB)
telemt_user_octets_to_client{user="hello"} 292893324532 (272.78 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 72660.1 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2204158
telemt_connections_bad_total 51207
telemt_handshake_timeouts_total 215613
telemt_upstream_connect_attempt_total 15584
telemt_upstream_connect_success_total 15505
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 15584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 13117
telemt_me_reconnect_success_total 11847
telemt_me_reader_eof_total 12553
telemt_me_idle_close_by_peer_total 12553
telemt_me_route_drop_no_conn_total 575184
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1385106
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3648
telemt_desync_full_logged_total 1311
telemt_desync_suppressed_total 2337
telemt_desync_frames_bucket_total{bucket="1_2"} 830
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1388
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12055
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11828
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 1380980
telemt_user_connections_current{user="hello"} 1442
telemt_user_octets_from_client{user="hello"} 25587852596 (23.83 GB)
telemt_user_octets_to_client{user="hello"} 519060748592 (483.41 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 72659.9 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1072931
telemt_connections_bad_total 82090
telemt_handshake_timeouts_total 52612
telemt_upstream_connect_attempt_total 171009
telemt_upstream_connect_success_total 170404
telemt_upstream_connect_fail_total 605
telemt_upstream_connect_attempts_per_request{bucket="1"} 171009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 156915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 605
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 61872
telemt_me_reconnect_success_total 13806
telemt_me_reader_eof_total 15682
telemt_me_idle_close_by_peer_total 15682
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 255947
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684124
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1911
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1378
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 685
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15452
telemt_me_refill_failed_total 1504
telemt_me_writer_restored_same_endpoint_total 13770
telemt_me_writer_restored_fallback_total 36
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1646
telemt_user_connections_total{user="hello"} 836637
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 15428350313 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 298491593656 (277.99 GB)
telemt_user_msgs_from_client{user="hello"} 3035962
telemt_user_msgs_to_client{user="hello"} 10927629
telemt_user_unique_ips_current{user="hello"} 242
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 72660.7 (20h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1088088
telemt_connections_bad_total 12682
telemt_handshake_timeouts_total 23503
telemt_upstream_connect_attempt_total 15906
telemt_upstream_connect_success_total 15821
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 15906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8475
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 15880
telemt_me_reconnect_success_total 12185
telemt_me_reader_eof_total 12999
telemt_me_idle_close_by_peer_total 12999
telemt_me_route_drop_no_conn_total 275544
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903207
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3162
telemt_desync_full_logged_total 1041
telemt_desync_suppressed_total 2121
telemt_desync_frames_bucket_total{bucket="1_2"} 955
telemt_desync_frames_bucket_total{bucket="3_10"} 1163
telemt_desync_frames_bucket_total{bucket="gt_10"} 1044
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 12448
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 12177
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 903230
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 11174572352 (10.41 GB)
telemt_user_octets_to_client{user="hello"} 316933027516 (295.17 GB)
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 114
```