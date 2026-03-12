# Server Metrics 2026-03-12 11:51:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 21176.6 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 718798
telemt_connections_bad_total 1499
telemt_handshake_timeouts_total 4084
telemt_upstream_connect_attempt_total 4146
telemt_upstream_connect_success_total 4118
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 321
telemt_me_reconnect_attempts_total 6914
telemt_me_reconnect_success_total 3021
telemt_me_reader_eof_total 3245
telemt_me_idle_close_by_peer_total 3245
telemt_me_route_drop_no_conn_total 252855
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 693510
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3459
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2581
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1265
telemt_desync_frames_bucket_total{bucket="gt_10"} 1313
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 3174
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3008
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 153
telemt_user_connections_total{user="hello"} 693362
telemt_user_connections_current{user="hello"} 1475
telemt_user_octets_from_client{user="hello"} 11954103768 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 193416396756 (180.13 GB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 50797.2 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373625
telemt_connections_bad_total 4453
telemt_handshake_timeouts_total 17951
telemt_upstream_connect_attempt_total 12475
telemt_upstream_connect_success_total 12468
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 906
telemt_me_reconnect_attempts_total 9795
telemt_me_reconnect_success_total 9739
telemt_me_reader_eof_total 10352
telemt_me_idle_close_by_peer_total 10352
telemt_me_route_drop_no_conn_total 106404
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330215
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 960
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 632
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 332
telemt_desync_frames_bucket_total{bucket="gt_10"} 274
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9828
telemt_me_writer_restored_same_endpoint_total 9730
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 330679
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 4533172091 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 115710962374 (107.76 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 50797.1 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860981
telemt_connections_bad_total 4320
telemt_handshake_timeouts_total 64094
telemt_upstream_connect_attempt_total 12500
telemt_upstream_connect_success_total 12495
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 12500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 770
telemt_me_reconnect_attempts_total 9677
telemt_me_reconnect_success_total 9595
telemt_me_reader_eof_total 10087
telemt_me_idle_close_by_peer_total 10087
telemt_me_route_drop_no_conn_total 206265
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577189
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2651
telemt_desync_full_logged_total 784
telemt_desync_suppressed_total 1867
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 922
telemt_desync_frames_bucket_total{bucket="gt_10"} 1375
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9617
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9554
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 577428
telemt_user_connections_current{user="hello"} 925
telemt_user_octets_from_client{user="hello"} 7678856172 (7.15 GB)
telemt_user_octets_to_client{user="hello"} 184759577653 (172.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 50797.5 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475273
telemt_connections_bad_total 7615
telemt_handshake_timeouts_total 43885
telemt_upstream_connect_attempt_total 13539
telemt_upstream_connect_success_total 13485
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 1132
telemt_me_reconnect_attempts_total 10983
telemt_me_reconnect_success_total 10937
telemt_me_reader_eof_total 11590
telemt_me_idle_close_by_peer_total 11590
telemt_me_route_drop_no_conn_total 154702
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393919
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11017
telemt_me_writer_restored_same_endpoint_total 10916
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 393742
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 4519396076 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 148603775920 (138.40 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 50797.3 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531687
telemt_connections_bad_total 1692
telemt_handshake_timeouts_total 4083
telemt_upstream_connect_attempt_total 16622
telemt_upstream_connect_success_total 16426
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 16622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 843
telemt_me_reconnect_attempts_total 17157
telemt_me_reconnect_success_total 13872
telemt_me_reader_eof_total 14446
telemt_me_idle_close_by_peer_total 14446
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 175503
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497804
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2098
telemt_desync_full_logged_total 701
telemt_desync_suppressed_total 1397
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 729
telemt_desync_frames_bucket_total{bucket="gt_10"} 750
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14109
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 13846
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 497725
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 5836854236 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 122492902420 (114.08 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 121
```