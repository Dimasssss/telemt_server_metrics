# Server Metrics 2026-03-13 03:56:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 79044.9 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2163671
telemt_connections_bad_total 28082
telemt_handshake_timeouts_total 23007
telemt_upstream_connect_attempt_total 15635
telemt_upstream_connect_success_total 15548
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1298
telemt_me_reconnect_attempts_total 20481
telemt_me_reconnect_success_total 11617
telemt_me_reader_eof_total 12545
telemt_me_idle_close_by_peer_total 12544
telemt_me_route_drop_no_conn_total 828509
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1990549
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8832
telemt_desync_full_logged_total 2296
telemt_desync_suppressed_total 6536
telemt_desync_frames_bucket_total{bucket="1_2"} 2319
telemt_desync_frames_bucket_total{bucket="3_10"} 3184
telemt_desync_frames_bucket_total{bucket="gt_10"} 3329
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12056
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11604
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 439
telemt_user_connections_total{user="hello"} 1989982
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 28857416824 (26.88 GB)
telemt_user_octets_to_client{user="hello"} 685773735976 (638.68 GB)
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 108665.5 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881166
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 39221
telemt_upstream_connect_attempt_total 27675
telemt_upstream_connect_success_total 27646
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3466
telemt_me_reconnect_attempts_total 20711
telemt_me_reconnect_success_total 20599
telemt_me_reader_eof_total 21950
telemt_me_idle_close_by_peer_total 21950
telemt_me_route_drop_no_conn_total 281467
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 794030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3132
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 2147
telemt_desync_frames_bucket_total{bucket="1_2"} 1269
telemt_desync_frames_bucket_total{bucket="3_10"} 1016
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 20799
telemt_me_writer_restored_same_endpoint_total 20590
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 795933
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 12683081196 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 308111572051 (286.95 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 108665.4 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1820805
telemt_connections_bad_total 13477
telemt_handshake_timeouts_total 120178
telemt_upstream_connect_attempt_total 25305
telemt_upstream_connect_success_total 25295
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1624
telemt_me_reconnect_attempts_total 20807
telemt_me_reconnect_success_total 19540
telemt_me_reader_eof_total 20701
telemt_me_idle_close_by_peer_total 20700
telemt_me_route_drop_no_conn_total 590375
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1436597
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5101
telemt_desync_full_logged_total 1557
telemt_desync_suppressed_total 3544
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 1844
telemt_desync_frames_bucket_total{bucket="gt_10"} 2441
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19723
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19499
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 1436207
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 24892002092 (23.18 GB)
telemt_user_octets_to_client{user="hello"} 514036201765 (478.73 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 108665.7 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131588
telemt_connections_bad_total 13169
telemt_handshake_timeouts_total 74540
telemt_upstream_connect_attempt_total 37667
telemt_upstream_connect_success_total 35386
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37393
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11381
telemt_me_reconnect_attempts_total 33046
telemt_me_reconnect_success_total 24116
telemt_me_reader_eof_total 26033
telemt_me_idle_close_by_peer_total 26026
telemt_me_route_drop_no_conn_total 401810
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 971759
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1924
telemt_desync_full_logged_total 636
telemt_desync_suppressed_total 1288
telemt_desync_frames_bucket_total{bucket="1_2"} 537
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 24553
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 24092
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 976942
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 14894345597 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 385470915898 (359.00 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 108665.5 (30h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1254994
telemt_connections_bad_total 12866
telemt_handshake_timeouts_total 10086
telemt_upstream_connect_attempt_total 34237
telemt_upstream_connect_success_total 33819
telemt_upstream_connect_fail_total 418
telemt_upstream_connect_attempts_per_request{bucket="1"} 34237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 418
telemt_me_keepalive_timeout_total 1915
telemt_me_reconnect_attempts_total 42150
telemt_me_reconnect_success_total 28419
telemt_me_reader_eof_total 29885
telemt_me_idle_close_by_peer_total 29885
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 466931
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1160568
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4288
telemt_desync_full_logged_total 1534
telemt_desync_suppressed_total 2754
telemt_desync_frames_bucket_total{bucket="1_2"} 1297
telemt_desync_frames_bucket_total{bucket="3_10"} 1403
telemt_desync_frames_bucket_total{bucket="gt_10"} 1588
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 29174
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 28369
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 755
telemt_user_connections_total{user="hello"} 1160422
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 14266045200 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 398905574772 (371.51 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 56
```