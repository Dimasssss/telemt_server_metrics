# Server Metrics 2026-03-12 09:08:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11386.9 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356052
telemt_connections_bad_total 1324
telemt_handshake_timeouts_total 2346
telemt_upstream_connect_attempt_total 2147
telemt_upstream_connect_success_total 2136
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1548
telemt_me_reconnect_success_total 1537
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 119835
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 344014
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1614
telemt_desync_full_logged_total 399
telemt_desync_suppressed_total 1215
telemt_desync_frames_bucket_total{bucket="1_2"} 399
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 619
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1551
telemt_me_writer_restored_same_endpoint_total 1524
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 343900
telemt_user_connections_current{user="hello"} 1232
telemt_user_octets_from_client{user="hello"} 5466120588 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 95500093980 (88.94 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41007.5 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235671
telemt_connections_bad_total 2866
telemt_handshake_timeouts_total 7719
telemt_upstream_connect_attempt_total 10494
telemt_upstream_connect_success_total 10488
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 641
telemt_me_reconnect_attempts_total 8296
telemt_me_reconnect_success_total 8253
telemt_me_reader_eof_total 8768
telemt_me_idle_close_by_peer_total 8768
telemt_me_route_drop_no_conn_total 67555
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207663
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 457
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 269
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 167
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8316
telemt_me_writer_restored_same_endpoint_total 8244
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 208055
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 3074371967 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 78888456770 (73.47 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41007.3 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647308
telemt_connections_bad_total 2998
telemt_handshake_timeouts_total 47938
telemt_upstream_connect_attempt_total 10536
telemt_upstream_connect_success_total 10531
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 8195
telemt_me_reconnect_success_total 8124
telemt_me_reader_eof_total 8534
telemt_me_idle_close_by_peer_total 8534
telemt_me_route_drop_no_conn_total 134237
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 385198
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1745
telemt_desync_full_logged_total 522
telemt_desync_suppressed_total 1223
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 925
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8122
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8083
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 385463
telemt_user_connections_current{user="hello"} 934
telemt_user_octets_from_client{user="hello"} 4867728332 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 129193861825 (120.32 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41007.7 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315944
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 22533
telemt_upstream_connect_attempt_total 11281
telemt_upstream_connect_success_total 11235
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 797
telemt_me_reconnect_attempts_total 9212
telemt_me_reconnect_success_total 9178
telemt_me_reader_eof_total 9741
telemt_me_idle_close_by_peer_total 9741
telemt_me_route_drop_no_conn_total 107449
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 523
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9236
telemt_me_writer_restored_same_endpoint_total 9157
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 264179
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 3106672464 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 95517348092 (88.96 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41007.6 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351932
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 2597
telemt_upstream_connect_attempt_total 13447
telemt_upstream_connect_success_total 13286
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 13447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 12741
telemt_me_reconnect_success_total 11225
telemt_me_reader_eof_total 11690
telemt_me_idle_close_by_peer_total 11690
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 113366
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332461
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1392
telemt_desync_full_logged_total 463
telemt_desync_suppressed_total 929
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11372
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11203
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 332403
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 3621322380 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 80533291660 (75.00 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 102
```