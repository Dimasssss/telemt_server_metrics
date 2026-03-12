# Server Metrics 2026-03-12 11:36:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 20258.1 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686544
telemt_connections_bad_total 1498
telemt_handshake_timeouts_total 3940
telemt_upstream_connect_attempt_total 3885
telemt_upstream_connect_success_total 3859
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 6699
telemt_me_reconnect_success_total 2807
telemt_me_reader_eof_total 3027
telemt_me_idle_close_by_peer_total 3027
telemt_me_route_drop_no_conn_total 239882
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662010
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3264
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1200
telemt_desync_frames_bucket_total{bucket="gt_10"} 1229
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2956
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 2794
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 661861
telemt_user_connections_current{user="hello"} 1386
telemt_user_octets_from_client{user="hello"} 11643217132 (10.84 GB)
telemt_user_octets_to_client{user="hello"} 183828643308 (171.20 GB)
telemt_user_unique_ips_current{user="hello"} 393
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 49878.8 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358926
telemt_connections_bad_total 4215
telemt_handshake_timeouts_total 14488
telemt_upstream_connect_attempt_total 12312
telemt_upstream_connect_success_total 12306
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 12312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6245
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 820
telemt_me_reconnect_attempts_total 9676
telemt_me_reconnect_success_total 9621
telemt_me_reader_eof_total 10230
telemt_me_idle_close_by_peer_total 10230
telemt_me_route_drop_no_conn_total 102807
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319473
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 835
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 244
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 9707
telemt_me_writer_restored_same_endpoint_total 9612
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 319941
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 4401468631 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 112785536290 (105.04 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 49878.6 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840927
telemt_connections_bad_total 4190
telemt_handshake_timeouts_total 62387
telemt_upstream_connect_attempt_total 12294
telemt_upstream_connect_success_total 12289
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5476
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 702
telemt_me_reconnect_attempts_total 9519
telemt_me_reconnect_success_total 9439
telemt_me_reader_eof_total 9931
telemt_me_idle_close_by_peer_total 9931
telemt_me_route_drop_no_conn_total 198947
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559426
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2536
telemt_desync_full_logged_total 751
telemt_desync_suppressed_total 1785
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 886
telemt_desync_frames_bucket_total{bucket="gt_10"} 1329
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9460
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9398
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 559669
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 7549839240 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 178762488261 (166.49 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 261
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 49879.1 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455408
telemt_connections_bad_total 2496
telemt_handshake_timeouts_total 42927
telemt_upstream_connect_attempt_total 13302
telemt_upstream_connect_success_total 13250
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 1001
telemt_me_reconnect_attempts_total 10793
telemt_me_reconnect_success_total 10748
telemt_me_reader_eof_total 11401
telemt_me_idle_close_by_peer_total 11401
telemt_me_route_drop_no_conn_total 150321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 10825
telemt_me_writer_restored_same_endpoint_total 10727
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 380178
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 4391035492 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 143809955920 (133.93 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 49878.8 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515459
telemt_connections_bad_total 1667
telemt_handshake_timeouts_total 3960
telemt_upstream_connect_attempt_total 16252
telemt_upstream_connect_success_total 16061
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 16252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_timeout_total 776
telemt_me_reconnect_attempts_total 15558
telemt_me_reconnect_success_total 13553
telemt_me_reader_eof_total 14088
telemt_me_idle_close_by_peer_total 14088
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 169037
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482716
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2034
telemt_desync_full_logged_total 675
telemt_desync_suppressed_total 1359
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 13748
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 13527
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 482641
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 5478095284 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 117901156796 (109.80 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 105
```