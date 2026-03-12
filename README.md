# Server Metrics 2026-03-12 16:52:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 39242.1 (10h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1418127
telemt_connections_bad_total 20252
telemt_handshake_timeouts_total 13477
telemt_upstream_connect_attempt_total 7884
telemt_upstream_connect_success_total 7839
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 469
telemt_me_reconnect_attempts_total 12189
telemt_me_reconnect_success_total 5842
telemt_me_reader_eof_total 6276
telemt_me_idle_close_by_peer_total 6275
telemt_me_route_drop_no_conn_total 520758
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1329367
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6792
telemt_desync_full_logged_total 1705
telemt_desync_suppressed_total 5087
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 2452
telemt_desync_frames_bucket_total{bucket="gt_10"} 2581
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6116
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 5829
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 1329038
telemt_user_connections_current{user="hello"} 1842
telemt_user_octets_from_client{user="hello"} 20201505864 (18.81 GB)
telemt_user_octets_to_client{user="hello"} 389691280008 (362.93 GB)
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 68862.7 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 621333
telemt_connections_bad_total 8104
telemt_handshake_timeouts_total 28695
telemt_upstream_connect_attempt_total 16487
telemt_upstream_connect_success_total 16480
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1299
telemt_me_reconnect_attempts_total 12925
telemt_me_reconnect_success_total 12852
telemt_me_reader_eof_total 13663
telemt_me_idle_close_by_peer_total 13663
telemt_me_route_drop_no_conn_total 190402
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557179
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2262
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1551
telemt_desync_frames_bucket_total{bucket="1_2"} 989
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 12981
telemt_me_writer_restored_same_endpoint_total 12843
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 557708
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 8590763095 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 198152037510 (184.54 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 68862.7 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1304803
telemt_connections_bad_total 6573
telemt_handshake_timeouts_total 94637
telemt_upstream_connect_attempt_total 16447
telemt_upstream_connect_success_total 16441
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1082
telemt_me_reconnect_attempts_total 13865
telemt_me_reconnect_success_total 12630
telemt_me_reader_eof_total 13318
telemt_me_idle_close_by_peer_total 13317
telemt_me_route_drop_no_conn_total 366117
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 976053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4189
telemt_desync_full_logged_total 1289
telemt_desync_suppressed_total 2900
telemt_desync_frames_bucket_total{bucket="1_2"} 651
telemt_desync_frames_bucket_total{bucket="3_10"} 1513
telemt_desync_frames_bucket_total{bucket="gt_10"} 2025
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12727
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 12589
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 976209
telemt_user_connections_current{user="hello"} 1203
telemt_user_octets_from_client{user="hello"} 14751557112 (13.74 GB)
telemt_user_octets_to_client{user="hello"} 315841327721 (294.15 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 68863.3 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 783793
telemt_connections_bad_total 7733
telemt_handshake_timeouts_total 61500
telemt_upstream_connect_attempt_total 18029
telemt_upstream_connect_success_total 17958
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 18029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 1519
telemt_me_reconnect_attempts_total 19755
telemt_me_reconnect_success_total 14505
telemt_me_reader_eof_total 15449
telemt_me_idle_close_by_peer_total 15449
telemt_me_route_drop_no_conn_total 271493
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678390
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1431
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 946
telemt_desync_frames_bucket_total{bucket="1_2"} 392
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 468
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14779
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 14484
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 677828
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 8361189492 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 264932069684 (246.74 GB)
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 68863.0 (19h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 885849
telemt_connections_bad_total 11390
telemt_handshake_timeouts_total 7231
telemt_upstream_connect_attempt_total 21790
telemt_upstream_connect_success_total 21526
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 21790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10400
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 1243
telemt_me_reconnect_attempts_total 25311
telemt_me_reconnect_success_total 18066
telemt_me_reader_eof_total 18891
telemt_me_idle_close_by_peer_total 18891
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 317539
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813671
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3205
telemt_desync_full_logged_total 1092
telemt_desync_suppressed_total 2113
telemt_desync_frames_bucket_total{bucket="1_2"} 870
telemt_desync_frames_bucket_total{bucket="3_10"} 1092
telemt_desync_frames_bucket_total{bucket="gt_10"} 1243
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 18485
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 18022
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 813558
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 10040102100 (9.35 GB)
telemt_user_octets_to_client{user="hello"} 235953133620 (219.75 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 112
```