# Server Metrics 2026-03-12 09:13:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11693.1 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366212
telemt_connections_bad_total 1324
telemt_handshake_timeouts_total 2379
telemt_upstream_connect_attempt_total 2162
telemt_upstream_connect_success_total 2151
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1563
telemt_me_reconnect_success_total 1552
telemt_me_reader_eof_total 1615
telemt_me_idle_close_by_peer_total 1615
telemt_me_route_drop_no_conn_total 123476
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353928
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 405
telemt_desync_suppressed_total 1238
telemt_desync_frames_bucket_total{bucket="1_2"} 407
telemt_desync_frames_bucket_total{bucket="3_10"} 606
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1566
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 353809
telemt_user_connections_current{user="hello"} 1345
telemt_user_octets_from_client{user="hello"} 5603823544 (5.22 GB)
telemt_user_octets_to_client{user="hello"} 98477900388 (91.71 GB)
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41313.4 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239567
telemt_connections_bad_total 2900
telemt_handshake_timeouts_total 7759
telemt_upstream_connect_attempt_total 10522
telemt_upstream_connect_success_total 10516
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 650
telemt_me_reconnect_attempts_total 8324
telemt_me_reconnect_success_total 8281
telemt_me_reader_eof_total 8799
telemt_me_idle_close_by_peer_total 8799
telemt_me_route_drop_no_conn_total 68573
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211405
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 460
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8346
telemt_me_writer_restored_same_endpoint_total 8272
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 211797
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 3119865039 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 80896016002 (75.34 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41313.3 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653735
telemt_connections_bad_total 3015
telemt_handshake_timeouts_total 48400
telemt_upstream_connect_attempt_total 10565
telemt_upstream_connect_success_total 10560
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 8224
telemt_me_reconnect_success_total 8153
telemt_me_reader_eof_total 8563
telemt_me_idle_close_by_peer_total 8563
telemt_me_route_drop_no_conn_total 136356
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391044
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1783
telemt_desync_full_logged_total 533
telemt_desync_suppressed_total 1250
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 945
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8151
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8112
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 391309
telemt_user_connections_current{user="hello"} 885
telemt_user_octets_from_client{user="hello"} 4906493844 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 130748786389 (121.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41313.6 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 320207
telemt_connections_bad_total 1815
telemt_handshake_timeouts_total 22760
telemt_upstream_connect_attempt_total 11312
telemt_upstream_connect_success_total 11266
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 803
telemt_me_reconnect_attempts_total 9243
telemt_me_reconnect_success_total 9209
telemt_me_reader_eof_total 9772
telemt_me_idle_close_by_peer_total 9772
telemt_me_route_drop_no_conn_total 108897
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 540
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9267
telemt_me_writer_restored_same_endpoint_total 9188
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 268180
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 3160438008 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 97218910308 (90.54 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41313.6 (11h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356691
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 2625
telemt_upstream_connect_attempt_total 13493
telemt_upstream_connect_success_total 13332
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 13493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 586
telemt_me_reconnect_attempts_total 12787
telemt_me_reconnect_success_total 11271
telemt_me_reader_eof_total 11736
telemt_me_idle_close_by_peer_total 11736
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 114788
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336821
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1413
telemt_desync_full_logged_total 469
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 413
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 507
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 11418
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11249
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 336763
telemt_user_connections_current{user="hello"} 671
telemt_user_octets_from_client{user="hello"} 3677301720 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 81428298908 (75.84 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 88
```