# Server Metrics 2026-03-12 23:36:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 63446.0 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1960027
telemt_connections_bad_total 26084
telemt_handshake_timeouts_total 21254
telemt_upstream_connect_attempt_total 12594
telemt_upstream_connect_success_total 12523
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 12594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 619
telemt_me_reconnect_attempts_total 18190
telemt_me_reconnect_success_total 9333
telemt_me_reader_eof_total 10077
telemt_me_idle_close_by_peer_total 10076
telemt_me_route_drop_no_conn_total 762869
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1822324
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8593
telemt_desync_full_logged_total 2242
telemt_desync_suppressed_total 6351
telemt_desync_frames_bucket_total{bucket="1_2"} 2266
telemt_desync_frames_bucket_total{bucket="3_10"} 3094
telemt_desync_frames_bucket_total{bucket="gt_10"} 3233
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9743
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 9320
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 410
telemt_user_connections_total{user="hello"} 1821789
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 27274388672 (25.40 GB)
telemt_user_octets_to_client{user="hello"} 645467012164 (601.14 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 93066.5 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 810135
telemt_connections_bad_total 11738
telemt_handshake_timeouts_total 31548
telemt_upstream_connect_attempt_total 23585
telemt_upstream_connect_success_total 23556
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 23585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3425
telemt_me_reconnect_attempts_total 17354
telemt_me_reconnect_success_total 17258
telemt_me_reader_eof_total 18371
telemt_me_idle_close_by_peer_total 18371
telemt_me_route_drop_no_conn_total 261928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732657
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3018
telemt_desync_full_logged_total 942
telemt_desync_suppressed_total 2076
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 989
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17430
telemt_me_writer_restored_same_endpoint_total 17249
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 734537
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 12138599720 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 283669838411 (264.19 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 93066.4 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1686336
telemt_connections_bad_total 8104
telemt_handshake_timeouts_total 113370
telemt_upstream_connect_attempt_total 21633
telemt_upstream_connect_success_total 21627
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 21633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1228
telemt_me_reconnect_attempts_total 17872
telemt_me_reconnect_success_total 16620
telemt_me_reader_eof_total 17578
telemt_me_idle_close_by_peer_total 17577
telemt_me_route_drop_no_conn_total 552927
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1318932
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4974
telemt_desync_full_logged_total 1526
telemt_desync_suppressed_total 3448
telemt_desync_frames_bucket_total{bucket="1_2"} 794
telemt_desync_frames_bucket_total{bucket="3_10"} 1797
telemt_desync_frames_bucket_total{bucket="gt_10"} 2383
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 16780
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 16579
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 1318537
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 19805601244 (18.45 GB)
telemt_user_octets_to_client{user="hello"} 485196053437 (451.87 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 93066.5 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1043471
telemt_connections_bad_total 13013
telemt_handshake_timeouts_total 71568
telemt_upstream_connect_attempt_total 32876
telemt_upstream_connect_success_total 30617
telemt_upstream_connect_fail_total 2122
telemt_upstream_connect_attempts_per_request{bucket="1"} 32602
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2121
telemt_me_keepalive_timeout_total 11250
telemt_me_reconnect_attempts_total 27938
telemt_me_reconnect_success_total 20100
telemt_me_reader_eof_total 21769
telemt_me_idle_close_by_peer_total 21762
telemt_me_route_drop_no_conn_total 369845
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 902887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1866
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1249
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 20464
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 20078
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 364
telemt_user_connections_total{user="hello"} 908107
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 14306178517 (13.32 GB)
telemt_user_octets_to_client{user="hello"} 361694158798 (336.85 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 93066.6 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1161347
telemt_connections_bad_total 12544
telemt_handshake_timeouts_total 9270
telemt_upstream_connect_attempt_total 28292
telemt_upstream_connect_success_total 27941
telemt_upstream_connect_fail_total 351
telemt_upstream_connect_attempts_per_request{bucket="1"} 28292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13552
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 351
telemt_me_keepalive_timeout_total 1461
telemt_me_reconnect_attempts_total 34325
telemt_me_reconnect_success_total 23285
telemt_me_reader_eof_total 24503
telemt_me_idle_close_by_peer_total 24503
telemt_me_seq_mismatch_total 34
telemt_me_route_drop_no_conn_total 433772
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070609
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 38
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4039
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 2627
telemt_desync_frames_bucket_total{bucket="1_2"} 1178
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 1517
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 23904
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 23240
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 619
telemt_user_connections_total{user="hello"} 1070467
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 13528365540 (12.60 GB)
telemt_user_octets_to_client{user="hello"} 377248487532 (351.34 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 27
```