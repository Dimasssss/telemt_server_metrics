# Server Metrics 2026-03-12 07:00:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 3739.4 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108705
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 1060
telemt_upstream_connect_attempt_total 773
telemt_upstream_connect_success_total 765
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 523
telemt_me_reconnect_success_total 520
telemt_me_reader_eof_total 510
telemt_me_idle_close_by_peer_total 510
telemt_me_route_drop_no_conn_total 34998
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104108
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 598
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 517
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 104054
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 1950702052 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 33040533544 (30.77 GB)
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33359.6 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148760
telemt_connections_bad_total 2009
telemt_handshake_timeouts_total 5776
telemt_upstream_connect_attempt_total 8703
telemt_upstream_connect_success_total 8698
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 6868
telemt_me_reconnect_success_total 6830
telemt_me_reader_eof_total 7263
telemt_me_idle_close_by_peer_total 7263
telemt_me_route_drop_no_conn_total 43460
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130945
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 387
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6887
telemt_me_writer_restored_same_endpoint_total 6821
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 131183
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 2006513007 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 56004651910 (52.16 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33359.5 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492704
telemt_connections_bad_total 2331
telemt_handshake_timeouts_total 36814
telemt_upstream_connect_attempt_total 8971
telemt_upstream_connect_success_total 8969
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 6998
telemt_me_reconnect_success_total 6932
telemt_me_reader_eof_total 7265
telemt_me_idle_close_by_peer_total 7265
telemt_me_route_drop_no_conn_total 82868
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245899
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1070
telemt_desync_full_logged_total 338
telemt_desync_suppressed_total 732
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 6917
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6891
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 246190
telemt_user_connections_current{user="hello"} 784
telemt_user_octets_from_client{user="hello"} 2674212160 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 86857261041 (80.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33359.8 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218258
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 13866
telemt_upstream_connect_attempt_total 9465
telemt_upstream_connect_success_total 9425
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 7782
telemt_me_reconnect_success_total 7754
telemt_me_reader_eof_total 8236
telemt_me_idle_close_by_peer_total 8236
telemt_me_route_drop_no_conn_total 70263
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 7800
telemt_me_writer_restored_same_endpoint_total 7733
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 177246
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 2002861952 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 55560721892 (51.74 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33359.5 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232257
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 1468
telemt_upstream_connect_attempt_total 11270
telemt_upstream_connect_success_total 11141
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 11270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 10970
telemt_me_reconnect_success_total 9458
telemt_me_reader_eof_total 9852
telemt_me_idle_close_by_peer_total 9852
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 71713
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219591
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 877
telemt_desync_full_logged_total 291
telemt_desync_suppressed_total 586
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9594
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9439
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 219547
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 2005167444 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 50745072288 (47.26 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 108
```