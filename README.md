# Server Metrics 2026-03-12 07:06:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 4045.1 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118568
telemt_connections_bad_total 1179
telemt_handshake_timeouts_total 1185
telemt_upstream_connect_attempt_total 870
telemt_upstream_connect_success_total 862
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 620
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 607
telemt_me_idle_close_by_peer_total 607
telemt_me_route_drop_no_conn_total 39095
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113675
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 618
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 614
telemt_me_writer_restored_same_endpoint_total 605
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_user_connections_total{user="hello"} 113622
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 2035532040 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 35366355248 (32.94 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33665.6 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152159
telemt_connections_bad_total 2009
telemt_handshake_timeouts_total 5887
telemt_upstream_connect_attempt_total 8790
telemt_upstream_connect_success_total 8785
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 8790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 213
telemt_me_reconnect_attempts_total 6939
telemt_me_reconnect_success_total 6901
telemt_me_reader_eof_total 7342
telemt_me_idle_close_by_peer_total 7342
telemt_me_route_drop_no_conn_total 44504
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134105
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6958
telemt_me_writer_restored_same_endpoint_total 6892
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 134341
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 2175731607 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 56716182390 (52.82 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 33665.4 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499505
telemt_connections_bad_total 2419
telemt_handshake_timeouts_total 37335
telemt_upstream_connect_attempt_total 9063
telemt_upstream_connect_success_total 9061
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 9063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 7070
telemt_me_reconnect_success_total 7003
telemt_me_reader_eof_total 7345
telemt_me_idle_close_by_peer_total 7345
telemt_me_route_drop_no_conn_total 85278
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251975
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1127
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6989
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 6962
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 252267
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 2724540060 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 90346839693 (84.14 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 33665.7 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222221
telemt_connections_bad_total 1741
telemt_handshake_timeouts_total 14099
telemt_upstream_connect_attempt_total 9562
telemt_upstream_connect_success_total 9522
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 9562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 251
telemt_me_reconnect_attempts_total 7852
telemt_me_reconnect_success_total 7824
telemt_me_reader_eof_total 8313
telemt_me_idle_close_by_peer_total 8313
telemt_me_route_drop_no_conn_total 72106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181076
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 305
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 7872
telemt_me_writer_restored_same_endpoint_total 7803
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 180943
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 2033139840 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 56937662956 (53.03 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 33665.6 (9h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236319
telemt_connections_bad_total 311
telemt_handshake_timeouts_total 1493
telemt_upstream_connect_attempt_total 11435
telemt_upstream_connect_success_total 11298
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 11435
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 209
telemt_me_reconnect_attempts_total 11099
telemt_me_reconnect_success_total 9587
telemt_me_reader_eof_total 9982
telemt_me_idle_close_by_peer_total 9982
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 73631
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223473
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 887
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 343
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 9725
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 9567
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 223428
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 2066135268 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 52284689464 (48.69 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 81
```