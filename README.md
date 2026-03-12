# Server Metrics 2026-03-12 17:48:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 42614.2 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1536943
telemt_connections_bad_total 20345
telemt_handshake_timeouts_total 14368
telemt_upstream_connect_attempt_total 8440
telemt_upstream_connect_success_total 8389
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 522
telemt_me_reconnect_attempts_total 15050
telemt_me_reconnect_success_total 6206
telemt_me_reader_eof_total 6729
telemt_me_idle_close_by_peer_total 6728
telemt_me_route_drop_no_conn_total 597985
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1440238
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7293
telemt_desync_full_logged_total 1855
telemt_desync_suppressed_total 5438
telemt_desync_frames_bucket_total{bucket="1_2"} 1883
telemt_desync_frames_bucket_total{bucket="3_10"} 2643
telemt_desync_frames_bucket_total{bucket="gt_10"} 2767
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6566
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 360
telemt_user_connections_total{user="hello"} 1439733
telemt_user_connections_current{user="hello"} 1710
telemt_user_octets_from_client{user="hello"} 21954905264 (20.45 GB)
telemt_user_octets_to_client{user="hello"} 465194736836 (433.25 GB)
telemt_user_unique_ips_current{user="hello"} 434
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 72234.4 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 667820
telemt_connections_bad_total 8709
telemt_handshake_timeouts_total 29138
telemt_upstream_connect_attempt_total 18615
telemt_upstream_connect_success_total 18586
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 18615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3297
telemt_me_reconnect_attempts_total 13382
telemt_me_reconnect_success_total 13298
telemt_me_reader_eof_total 14139
telemt_me_idle_close_by_peer_total 14139
telemt_me_route_drop_no_conn_total 210494
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2520
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1748
telemt_desync_frames_bucket_total{bucket="1_2"} 1043
telemt_desync_frames_bucket_total{bucket="3_10"} 822
telemt_desync_frames_bucket_total{bucket="gt_10"} 655
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 13437
telemt_me_writer_restored_same_endpoint_total 13289
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 601618
telemt_user_connections_current{user="hello"} 548
telemt_user_octets_from_client{user="hello"} 9124218420 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 226791045267 (211.22 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 72234.4 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388668
telemt_connections_bad_total 6716
telemt_handshake_timeouts_total 98508
telemt_upstream_connect_attempt_total 17199
telemt_upstream_connect_success_total 17194
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 17199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1139
telemt_me_reconnect_attempts_total 14436
telemt_me_reconnect_success_total 13198
telemt_me_reader_eof_total 13919
telemt_me_idle_close_by_peer_total 13918
telemt_me_route_drop_no_conn_total 451018
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4451
telemt_desync_full_logged_total 1384
telemt_desync_suppressed_total 3067
telemt_desync_frames_bucket_total{bucket="1_2"} 685
telemt_desync_frames_bucket_total{bucket="3_10"} 1624
telemt_desync_frames_bucket_total{bucket="gt_10"} 2142
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 13306
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 13157
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 1053458
telemt_user_connections_current{user="hello"} 1014
telemt_user_octets_from_client{user="hello"} 15794460468 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 371484682789 (345.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 72234.8 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838421
telemt_connections_bad_total 10148
telemt_handshake_timeouts_total 63880
telemt_upstream_connect_attempt_total 18892
telemt_upstream_connect_success_total 18819
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 18892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1586
telemt_me_reconnect_attempts_total 21590
telemt_me_reconnect_success_total 15184
telemt_me_reader_eof_total 16183
telemt_me_idle_close_by_peer_total 16183
telemt_me_route_drop_no_conn_total 293806
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1088
telemt_desync_frames_bucket_total{bucket="1_2"} 447
telemt_desync_frames_bucket_total{bucket="3_10"} 633
telemt_desync_frames_bucket_total{bucket="gt_10"} 556
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15503
telemt_me_refill_failed_total 198
telemt_me_writer_restored_same_endpoint_total 15163
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 725783
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 8889853880 (8.28 GB)
telemt_user_octets_to_client{user="hello"} 293820356504 (273.64 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 72234.7 (20h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 944835
telemt_connections_bad_total 11403
telemt_handshake_timeouts_total 7715
telemt_upstream_connect_attempt_total 23011
telemt_upstream_connect_success_total 22737
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10985
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1301
telemt_me_reconnect_attempts_total 30111
telemt_me_reconnect_success_total 19083
telemt_me_reader_eof_total 20049
telemt_me_idle_close_by_peer_total 20049
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 348502
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 867570
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3351
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 2199
telemt_desync_frames_bucket_total{bucket="1_2"} 912
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 1293
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 19644
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 19039
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 867451
telemt_user_connections_current{user="hello"} 786
telemt_user_octets_from_client{user="hello"} 10631712028 (9.90 GB)
telemt_user_octets_to_client{user="hello"} 270553041812 (251.97 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 105
```