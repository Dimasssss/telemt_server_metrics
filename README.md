# Server Metrics 2026-03-14 01:58:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 158409.8 (44h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4650951
telemt_connections_bad_total 39807
telemt_handshake_timeouts_total 108282
telemt_upstream_connect_attempt_total 33433
telemt_upstream_connect_success_total 33211
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 33433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 6706
telemt_me_reconnect_attempts_total 33139
telemt_me_reconnect_success_total 23001
telemt_me_reader_eof_total 24665
telemt_me_idle_close_by_peer_total 24664
telemt_me_route_drop_no_conn_total 1760469
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4263967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16730
telemt_desync_full_logged_total 4510
telemt_desync_suppressed_total 12220
telemt_desync_frames_bucket_total{bucket="1_2"} 4177
telemt_desync_frames_bucket_total{bucket="3_10"} 6388
telemt_desync_frames_bucket_total{bucket="gt_10"} 6165
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 23650
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22988
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 649
telemt_user_connections_total{user="hello"} 4265823
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 62734144316 (58.43 GB)
telemt_user_octets_to_client{user="hello"} 1346939577609 (1.23 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 58073.5 (16h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688561
telemt_connections_bad_total 50961
telemt_handshake_timeouts_total 13053
telemt_upstream_connect_attempt_total 16157
telemt_upstream_connect_success_total 15908
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 16157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6777
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 2055
telemt_me_reconnect_attempts_total 14417
telemt_me_reconnect_success_total 10974
telemt_me_reader_eof_total 11649
telemt_me_idle_close_by_peer_total 11648
telemt_me_route_drop_no_conn_total 231721
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 552249
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1654
telemt_desync_full_logged_total 450
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 717
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11234
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10966
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 554200
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 5940977065 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 178194495216 (165.96 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 188030.3 (52h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3365124
telemt_connections_bad_total 34929
telemt_handshake_timeouts_total 223170
telemt_upstream_connect_attempt_total 42268
telemt_upstream_connect_success_total 42247
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 42268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10410
telemt_me_reconnect_attempts_total 37549
telemt_me_reconnect_success_total 32589
telemt_me_reader_eof_total 34598
telemt_me_idle_close_by_peer_total 34597
telemt_me_route_drop_no_conn_total 1154104
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2798995
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9232
telemt_desync_full_logged_total 3099
telemt_desync_suppressed_total 6133
telemt_desync_frames_bucket_total{bucket="1_2"} 1567
telemt_desync_frames_bucket_total{bucket="3_10"} 3344
telemt_desync_frames_bucket_total{bucket="gt_10"} 4321
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 33047
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 32548
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 458
telemt_user_connections_total{user="hello"} 2798229
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 45084892240 (41.99 GB)
telemt_user_octets_to_client{user="hello"} 1001633590577 (932.84 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 188032.9 (52h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2244241
telemt_connections_bad_total 22941
telemt_handshake_timeouts_total 243796
telemt_upstream_connect_attempt_total 58844
telemt_upstream_connect_success_total 56385
telemt_upstream_connect_fail_total 2322
telemt_upstream_connect_attempts_per_request{bucket="1"} 58570
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2321
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20410
telemt_me_reconnect_attempts_total 49049
telemt_me_reconnect_success_total 40019
telemt_me_reader_eof_total 42906
telemt_me_idle_close_by_peer_total 42899
telemt_me_route_drop_no_conn_total 769663
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1794237
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3806
telemt_desync_full_logged_total 1223
telemt_desync_suppressed_total 2583
telemt_desync_frames_bucket_total{bucket="1_2"} 1012
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 40647
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 39995
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 1800158
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 27465273055 (25.58 GB)
telemt_user_octets_to_client{user="hello"} 665207328770 (619.52 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 57466.2 (15h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690502
telemt_connections_bad_total 7904
telemt_handshake_timeouts_total 8645
telemt_upstream_connect_attempt_total 14442
telemt_upstream_connect_success_total 14042
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 14442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 43335
telemt_me_reconnect_success_total 11171
telemt_me_reader_eof_total 12463
telemt_me_idle_close_by_peer_total 12462
telemt_me_route_drop_no_conn_total 262004
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642751
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1656
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1138
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 511
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12276
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 11166
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1105
telemt_user_connections_total{user="hello"} 642638
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 10596352816 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 210004999556 (195.58 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 21
```