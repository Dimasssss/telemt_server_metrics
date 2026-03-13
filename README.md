# Server Metrics 2026-03-13 15:36:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 121049.4 (33h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3771101
telemt_connections_bad_total 37426
telemt_handshake_timeouts_total 77637
telemt_upstream_connect_attempt_total 23572
telemt_upstream_connect_success_total 23437
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 23572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2196
telemt_me_reconnect_attempts_total 27508
telemt_me_reconnect_success_total 17420
telemt_me_reader_eof_total 18722
telemt_me_idle_close_by_peer_total 18721
telemt_me_route_drop_no_conn_total 1401090
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3455928
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13968
telemt_desync_full_logged_total 3688
telemt_desync_suppressed_total 10280
telemt_desync_frames_bucket_total{bucket="1_2"} 3508
telemt_desync_frames_bucket_total{bucket="3_10"} 5288
telemt_desync_frames_bucket_total{bucket="gt_10"} 5172
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 17974
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17407
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 3455733
telemt_user_connections_current{user="hello"} 1658
telemt_user_octets_from_client{user="hello"} 47160312704 (43.92 GB)
telemt_user_octets_to_client{user="hello"} 1084253876444 (1009.79 GB)
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 20713.2 (5h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296747
telemt_connections_bad_total 15396
telemt_handshake_timeouts_total 7939
telemt_upstream_connect_attempt_total 4854
telemt_upstream_connect_success_total 4768
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 4854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 5998
telemt_me_reconnect_success_total 3707
telemt_me_reader_eof_total 3936
telemt_me_idle_close_by_peer_total 3936
telemt_me_route_drop_no_conn_total 108241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265806
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 760
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 332
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3824
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3700
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 265830
telemt_user_connections_current{user="hello"} 516
telemt_user_octets_from_client{user="hello"} 2665197352 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 76073440680 (70.85 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 150670.0 (41h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2793177
telemt_connections_bad_total 27793
telemt_handshake_timeouts_total 186800
telemt_upstream_connect_attempt_total 33846
telemt_upstream_connect_success_total 33836
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3273
telemt_me_reconnect_attempts_total 28547
telemt_me_reconnect_success_total 25998
telemt_me_reader_eof_total 27571
telemt_me_idle_close_by_peer_total 27570
telemt_me_route_drop_no_conn_total 943438
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2293099
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8157
telemt_desync_full_logged_total 2700
telemt_desync_suppressed_total 5457
telemt_desync_frames_bucket_total{bucket="1_2"} 1295
telemt_desync_frames_bucket_total{bucket="3_10"} 2966
telemt_desync_frames_bucket_total{bucket="gt_10"} 3896
telemt_pool_swap_total 142
telemt_me_writer_removed_unexpected_total 26302
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25957
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 2292497
telemt_user_connections_current{user="hello"} 993
telemt_user_octets_from_client{user="hello"} 37923080688 (35.32 GB)
telemt_user_octets_to_client{user="hello"} 802915147633 (747.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 150670.4 (41h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1777272
telemt_connections_bad_total 18137
telemt_handshake_timeouts_total 136840
telemt_upstream_connect_attempt_total 47553
telemt_upstream_connect_success_total 45222
telemt_upstream_connect_fail_total 2194
telemt_upstream_connect_attempts_per_request{bucket="1"} 47279
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11880
telemt_me_reconnect_attempts_total 40835
telemt_me_reconnect_success_total 31862
telemt_me_reader_eof_total 34232
telemt_me_idle_close_by_peer_total 34225
telemt_me_route_drop_no_conn_total 637374
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1483301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2983
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2016
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1231
telemt_desync_frames_bucket_total{bucket="gt_10"} 949
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 32386
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 31838
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 1488010
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 23164521197 (21.57 GB)
telemt_user_octets_to_client{user="hello"} 571294943686 (532.06 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 20106.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322697
telemt_connections_bad_total 4005
telemt_handshake_timeouts_total 3015
telemt_upstream_connect_attempt_total 4334
telemt_upstream_connect_success_total 4201
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 4334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2205
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 13729
telemt_me_reconnect_success_total 3155
telemt_me_reader_eof_total 3534
telemt_me_idle_close_by_peer_total 3534
telemt_me_route_drop_no_conn_total 128378
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302571
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 930
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 631
telemt_desync_frames_bucket_total{bucket="1_2"} 324
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 236
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3502
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 3151
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 302547
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 3553929900 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 94890435196 (88.37 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 118
```