# Server Metrics 2026-03-12 13:08:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25767.8 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889112
telemt_connections_bad_total 4648
telemt_handshake_timeouts_total 7769
telemt_upstream_connect_attempt_total 5068
telemt_upstream_connect_success_total 5037
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 5068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 7612
telemt_me_reconnect_success_total 3714
telemt_me_reader_eof_total 3985
telemt_me_idle_close_by_peer_total 3984
telemt_me_route_drop_no_conn_total 316018
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851355
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4533
telemt_desync_full_logged_total 1146
telemt_desync_suppressed_total 3387
telemt_desync_frames_bucket_total{bucket="1_2"} 1131
telemt_desync_frames_bucket_total{bucket="3_10"} 1645
telemt_desync_frames_bucket_total{bucket="gt_10"} 1757
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3877
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3701
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 851178
telemt_user_connections_current{user="hello"} 1573
telemt_user_octets_from_client{user="hello"} 14262143384 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 251038688708 (233.80 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 55388.2 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 440351
telemt_connections_bad_total 5262
telemt_handshake_timeouts_total 23853
telemt_upstream_connect_attempt_total 13436
telemt_upstream_connect_success_total 13429
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1068
telemt_me_reconnect_attempts_total 10538
telemt_me_reconnect_success_total 10480
telemt_me_reader_eof_total 11142
telemt_me_idle_close_by_peer_total 11142
telemt_me_route_drop_no_conn_total 126706
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388596
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1321
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 894
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10576
telemt_me_writer_restored_same_endpoint_total 10471
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 389051
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 5820109475 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 139534844650 (129.95 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 55388.1 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 977250
telemt_connections_bad_total 5342
telemt_handshake_timeouts_total 73933
telemt_upstream_connect_attempt_total 13424
telemt_upstream_connect_success_total 13419
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10384
telemt_me_reconnect_success_total 10293
telemt_me_reader_eof_total 10843
telemt_me_idle_close_by_peer_total 10843
telemt_me_route_drop_no_conn_total 245014
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680168
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3025
telemt_desync_full_logged_total 910
telemt_desync_suppressed_total 2115
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 1085
telemt_desync_frames_bucket_total{bucket="gt_10"} 1511
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 10324
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10252
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 680391
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 8932817112 (8.32 GB)
telemt_user_octets_to_client{user="hello"} 216769398697 (201.88 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 55388.6 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552219
telemt_connections_bad_total 7644
telemt_handshake_timeouts_total 51951
telemt_upstream_connect_attempt_total 14836
telemt_upstream_connect_success_total 14776
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 14836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 1272
telemt_me_reconnect_attempts_total 13237
telemt_me_reconnect_success_total 12005
telemt_me_reader_eof_total 12738
telemt_me_idle_close_by_peer_total 12738
telemt_me_route_drop_no_conn_total 185498
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462078
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 940
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 613
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 388
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12134
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11984
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 461590
telemt_user_connections_current{user="hello"} 644
telemt_user_octets_from_client{user="hello"} 5208084204 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 184727561600 (172.04 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 55388.5 (15h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622231
telemt_connections_bad_total 1713
telemt_handshake_timeouts_total 5049
telemt_upstream_connect_attempt_total 17732
telemt_upstream_connect_success_total 17517
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 17732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8516
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 21965
telemt_me_reconnect_success_total 14740
telemt_me_reader_eof_total 15453
telemt_me_idle_close_by_peer_total 15453
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 211516
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580366
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2427
telemt_desync_full_logged_total 820
telemt_desync_suppressed_total 1607
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 855
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 15108
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14713
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 580279
telemt_user_connections_current{user="hello"} 822
telemt_user_octets_from_client{user="hello"} 6687976268 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 152347742300 (141.88 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 117
```