# Server Metrics 2026-03-14 05:48:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 172213.3 (47h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4859559
telemt_connections_bad_total 40022
telemt_handshake_timeouts_total 112368
telemt_upstream_connect_attempt_total 36253
telemt_upstream_connect_success_total 36016
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 36253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 7308
telemt_me_reconnect_attempts_total 35252
telemt_me_reconnect_success_total 25106
telemt_me_reader_eof_total 26948
telemt_me_idle_close_by_peer_total 26947
telemt_me_route_drop_no_conn_total 1839742
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4458404
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17135
telemt_desync_full_logged_total 4625
telemt_desync_suppressed_total 12510
telemt_desync_frames_bucket_total{bucket="1_2"} 4274
telemt_desync_frames_bucket_total{bucket="3_10"} 6551
telemt_desync_frames_bucket_total{bucket="gt_10"} 6310
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 25782
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 25093
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 676
telemt_user_connections_total{user="hello"} 4459945
telemt_user_connections_current{user="hello"} 1054
telemt_user_octets_from_client{user="hello"} 65189203668 (60.71 GB)
telemt_user_octets_to_client{user="hello"} 1407718408465 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 71877.3 (19h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784310
telemt_connections_bad_total 53075
telemt_handshake_timeouts_total 14499
telemt_upstream_connect_attempt_total 19649
telemt_upstream_connect_success_total 19381
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2115
telemt_me_reconnect_attempts_total 17243
telemt_me_reconnect_success_total 13784
telemt_me_reader_eof_total 14651
telemt_me_idle_close_by_peer_total 14650
telemt_me_route_drop_no_conn_total 255740
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618903
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1848
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1295
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 825
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 14083
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13776
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 299
telemt_user_connections_total{user="hello"} 620855
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 6593406353 (6.14 GB)
telemt_user_octets_to_client{user="hello"} 209531996680 (195.14 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 201834.0 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3490477
telemt_connections_bad_total 38115
telemt_handshake_timeouts_total 230712
telemt_upstream_connect_attempt_total 45647
telemt_upstream_connect_success_total 45626
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10631
telemt_me_reconnect_attempts_total 40236
telemt_me_reconnect_success_total 35265
telemt_me_reader_eof_total 37468
telemt_me_idle_close_by_peer_total 37467
telemt_me_route_drop_no_conn_total 1193695
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2909058
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9593
telemt_desync_full_logged_total 3227
telemt_desync_suppressed_total 6366
telemt_desync_frames_bucket_total{bucket="1_2"} 1666
telemt_desync_frames_bucket_total{bucket="3_10"} 3470
telemt_desync_frames_bucket_total{bucket="gt_10"} 4457
telemt_pool_swap_total 192
telemt_me_writer_removed_unexpected_total 35755
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35224
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 2908269
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 47174751812 (43.93 GB)
telemt_user_octets_to_client{user="hello"} 1041409086525 (969.89 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 201836.6 (56h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2336874
telemt_connections_bad_total 23151
telemt_handshake_timeouts_total 269548
telemt_upstream_connect_attempt_total 63028
telemt_upstream_connect_success_total 60546
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62754
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20481
telemt_me_reconnect_attempts_total 52513
telemt_me_reconnect_success_total 43471
telemt_me_reader_eof_total 46617
telemt_me_idle_close_by_peer_total 46610
telemt_me_route_drop_no_conn_total 790405
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1849099
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3888
telemt_desync_full_logged_total 1255
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1616
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 44131
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43447
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 1855094
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 28097927955 (26.17 GB)
telemt_user_octets_to_client{user="hello"} 681564995886 (634.76 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 71269.8 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 760679
telemt_connections_bad_total 8030
telemt_handshake_timeouts_total 9013
telemt_upstream_connect_attempt_total 18449
telemt_upstream_connect_success_total 17958
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 18449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 56521
telemt_me_reconnect_success_total 14384
telemt_me_reader_eof_total 16056
telemt_me_idle_close_by_peer_total 16055
telemt_me_route_drop_no_conn_total 291815
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710358
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1755
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1196
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15826
telemt_me_refill_failed_total 1312
telemt_me_writer_restored_same_endpoint_total 14379
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1442
telemt_user_connections_total{user="hello"} 710224
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 12704480040 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 236980080464 (220.70 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 55
```