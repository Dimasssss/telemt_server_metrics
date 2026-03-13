# Server Metrics 2026-03-13 09:43:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 99867.8 (27h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2856659
telemt_connections_bad_total 36407
telemt_handshake_timeouts_total 41902
telemt_upstream_connect_attempt_total 19625
telemt_upstream_connect_success_total 19517
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 19625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 1414
telemt_me_reconnect_attempts_total 24636
telemt_me_reconnect_success_total 14573
telemt_me_reader_eof_total 15703
telemt_me_idle_close_by_peer_total 15702
telemt_me_route_drop_no_conn_total 1059819
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2611591
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11406
telemt_desync_full_logged_total 2954
telemt_desync_suppressed_total 8452
telemt_desync_frames_bucket_total{bucket="1_2"} 2927
telemt_desync_frames_bucket_total{bucket="3_10"} 4268
telemt_desync_frames_bucket_total{bucket="gt_10"} 4211
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 15090
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 14560
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 2611349
telemt_user_connections_current{user="hello"} 1739
telemt_user_octets_from_client{user="hello"} 36313614596 (33.82 GB)
telemt_user_octets_to_client{user="hello"} 851510072068 (793.03 GB)
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 129487.8 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1163358
telemt_connections_bad_total 14553
telemt_handshake_timeouts_total 106647
telemt_upstream_connect_attempt_total 32081
telemt_upstream_connect_success_total 32050
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 32081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3733
telemt_me_reconnect_attempts_total 24117
telemt_me_reconnect_success_total 23991
telemt_me_reader_eof_total 25568
telemt_me_idle_close_by_peer_total 25568
telemt_me_route_drop_no_conn_total 358416
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1000459
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4409
telemt_desync_full_logged_total 1335
telemt_desync_suppressed_total 3074
telemt_desync_frames_bucket_total{bucket="1_2"} 1604
telemt_desync_frames_bucket_total{bucket="3_10"} 1457
telemt_desync_frames_bucket_total{bucket="gt_10"} 1348
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 24225
telemt_me_writer_restored_same_endpoint_total 23982
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 1002385
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 15257795976 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 366982444379 (341.78 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 129487.7 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2235738
telemt_connections_bad_total 24668
telemt_handshake_timeouts_total 150535
telemt_upstream_connect_attempt_total 29673
telemt_upstream_connect_success_total 29663
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 29673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14001
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1834
telemt_me_reconnect_attempts_total 24171
telemt_me_reconnect_success_total 22883
telemt_me_reader_eof_total 24239
telemt_me_idle_close_by_peer_total 24238
telemt_me_route_drop_no_conn_total 729107
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1789696
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5915
telemt_desync_full_logged_total 1886
telemt_desync_suppressed_total 4029
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 2161
telemt_desync_frames_bucket_total{bucket="gt_10"} 2789
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 23111
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22842
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 1789126
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 31191165860 (29.05 GB)
telemt_user_octets_to_client{user="hello"} 643963115313 (599.74 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 129488.1 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1416874
telemt_connections_bad_total 14234
telemt_handshake_timeouts_total 87521
telemt_upstream_connect_attempt_total 42573
telemt_upstream_connect_success_total 40268
telemt_upstream_connect_fail_total 2168
telemt_upstream_connect_attempts_per_request{bucket="1"} 42299
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2167
telemt_me_keepalive_timeout_total 11471
telemt_me_reconnect_attempts_total 36929
telemt_me_reconnect_success_total 27986
telemt_me_reader_eof_total 30132
telemt_me_idle_close_by_peer_total 30125
telemt_me_route_drop_no_conn_total 499459
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182416
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2225
telemt_desync_full_logged_total 732
telemt_desync_suppressed_total 1493
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 757
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28467
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27962
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 1187178
telemt_user_connections_current{user="hello"} 536
telemt_user_octets_from_client{user="hello"} 18035400777 (16.80 GB)
telemt_user_octets_to_client{user="hello"} 471626769186 (439.24 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 129488.0 (35h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1580473
telemt_connections_bad_total 36063
telemt_handshake_timeouts_total 12856
telemt_upstream_connect_attempt_total 41491
telemt_upstream_connect_success_total 40998
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 41491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_timeout_total 2246
telemt_me_reconnect_attempts_total 51166
telemt_me_reconnect_success_total 34567
telemt_me_reader_eof_total 36279
telemt_me_idle_close_by_peer_total 36279
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 578656
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1441257
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 52
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 5003
telemt_desync_full_logged_total 1784
telemt_desync_suppressed_total 3219
telemt_desync_frames_bucket_total{bucket="1_2"} 1526
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1861
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 35463
telemt_me_refill_failed_total 514
telemt_me_writer_restored_same_endpoint_total 34506
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 1441057
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 18454484272 (17.19 GB)
telemt_user_octets_to_client{user="hello"} 497881462944 (463.69 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 120
```