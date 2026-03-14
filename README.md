# Server Metrics 2026-03-14 04:37:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 167918.5 (46h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4772384
telemt_connections_bad_total 39900
telemt_handshake_timeouts_total 109925
telemt_upstream_connect_attempt_total 35430
telemt_upstream_connect_success_total 35198
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7297
telemt_me_reconnect_attempts_total 34651
telemt_me_reconnect_success_total 24508
telemt_me_reader_eof_total 26304
telemt_me_idle_close_by_peer_total 26303
telemt_me_route_drop_no_conn_total 1809082
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4377772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16900
telemt_desync_full_logged_total 4563
telemt_desync_suppressed_total 12337
telemt_desync_frames_bucket_total{bucket="1_2"} 4217
telemt_desync_frames_bucket_total{bucket="3_10"} 6453
telemt_desync_frames_bucket_total{bucket="gt_10"} 6230
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 25173
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24495
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 4379343
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 64059422248 (59.66 GB)
telemt_user_octets_to_client{user="hello"} 1380339752353 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 67582.1 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740780
telemt_connections_bad_total 52727
telemt_handshake_timeouts_total 13574
telemt_upstream_connect_attempt_total 18616
telemt_upstream_connect_success_total 18355
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2100
telemt_me_reconnect_attempts_total 16398
telemt_me_reconnect_success_total 12945
telemt_me_reader_eof_total 13744
telemt_me_idle_close_by_peer_total 13743
telemt_me_route_drop_no_conn_total 246070
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590221
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1771
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 785
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13230
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12937
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 592172
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 6323149165 (5.89 GB)
telemt_user_octets_to_client{user="hello"} 197638760736 (184.07 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 197539.1 (54h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3437073
telemt_connections_bad_total 37033
telemt_handshake_timeouts_total 226968
telemt_upstream_connect_attempt_total 44691
telemt_upstream_connect_success_total 44670
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20916
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10605
telemt_me_reconnect_attempts_total 39497
telemt_me_reconnect_success_total 34528
telemt_me_reader_eof_total 36684
telemt_me_idle_close_by_peer_total 36683
telemt_me_route_drop_no_conn_total 1175146
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2863443
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9487
telemt_desync_full_logged_total 3185
telemt_desync_suppressed_total 6302
telemt_desync_frames_bucket_total{bucket="1_2"} 1642
telemt_desync_frames_bucket_total{bucket="3_10"} 3431
telemt_desync_frames_bucket_total{bucket="gt_10"} 4414
telemt_pool_swap_total 187
telemt_me_writer_removed_unexpected_total 35009
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34487
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 2862659
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 45749338080 (42.61 GB)
telemt_user_octets_to_client{user="hello"} 1025599323881 (955.16 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 197541.7 (54h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304540
telemt_connections_bad_total 23071
telemt_handshake_timeouts_total 259045
telemt_upstream_connect_attempt_total 61773
telemt_upstream_connect_success_total 59300
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61499
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20459
telemt_me_reconnect_attempts_total 51485
telemt_me_reconnect_success_total 42446
telemt_me_reader_eof_total 45526
telemt_me_idle_close_by_peer_total 45519
telemt_me_route_drop_no_conn_total 782293
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1828913
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3881
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2632
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1613
telemt_desync_frames_bucket_total{bucket="gt_10"} 1224
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 43096
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42422
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 650
telemt_user_connections_total{user="hello"} 1834864
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 27778922331 (25.87 GB)
telemt_user_octets_to_client{user="hello"} 674276076822 (627.97 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66975.1 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 732695
telemt_connections_bad_total 7978
telemt_handshake_timeouts_total 8748
telemt_upstream_connect_attempt_total 17292
telemt_upstream_connect_success_total 16833
telemt_upstream_connect_fail_total 459
telemt_upstream_connect_attempts_per_request{bucket="1"} 17292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 459
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 52241
telemt_me_reconnect_success_total 13481
telemt_me_reader_eof_total 15036
telemt_me_idle_close_by_peer_total 15035
telemt_me_route_drop_no_conn_total 279781
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 683779
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1722
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1181
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 539
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 14806
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13476
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 683647
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 12408283036 (11.56 GB)
telemt_user_octets_to_client{user="hello"} 220684719660 (205.53 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 46
```