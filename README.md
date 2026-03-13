# Server Metrics 2026-03-13 18:09:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 130227.8 (36h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4160098
telemt_connections_bad_total 37531
telemt_handshake_timeouts_total 101988
telemt_upstream_connect_attempt_total 27500
telemt_upstream_connect_success_total 27321
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 27500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15110
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12090
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 5757
telemt_me_reconnect_attempts_total 28592
telemt_me_reconnect_success_total 18485
telemt_me_reader_eof_total 19859
telemt_me_idle_close_by_peer_total 19858
telemt_me_route_drop_no_conn_total 1553019
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3800928
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14818
telemt_desync_full_logged_total 3947
telemt_desync_suppressed_total 10871
telemt_desync_frames_bucket_total{bucket="1_2"} 3668
telemt_desync_frames_bucket_total{bucket="3_10"} 5626
telemt_desync_frames_bucket_total{bucket="gt_10"} 5524
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19064
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18472
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 3803099
telemt_user_connections_current{user="hello"} 1562
telemt_user_octets_from_client{user="hello"} 53407285328 (49.74 GB)
telemt_user_octets_to_client{user="hello"} 1181728239349 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29891.7 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445848
telemt_connections_bad_total 34355
telemt_handshake_timeouts_total 10578
telemt_upstream_connect_attempt_total 8487
telemt_upstream_connect_success_total 8309
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 8487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 1602
telemt_me_reconnect_attempts_total 8747
telemt_me_reconnect_success_total 5349
telemt_me_reader_eof_total 5662
telemt_me_idle_close_by_peer_total 5661
telemt_me_route_drop_no_conn_total 167799
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 388038
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1352
telemt_desync_full_logged_total 351
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 267
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 458
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5526
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5341
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 389374
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 4046241243 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 120032730316 (111.79 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 159848.3 (44h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3041367
telemt_connections_bad_total 28778
telemt_handshake_timeouts_total 203504
telemt_upstream_connect_attempt_total 35637
telemt_upstream_connect_success_total 35627
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3511
telemt_me_reconnect_attempts_total 29897
telemt_me_reconnect_success_total 27342
telemt_me_reader_eof_total 28992
telemt_me_idle_close_by_peer_total 28991
telemt_me_route_drop_no_conn_total 1039411
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2515872
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8531
telemt_desync_full_logged_total 2829
telemt_desync_suppressed_total 5702
telemt_desync_frames_bucket_total{bucket="1_2"} 1380
telemt_desync_frames_bucket_total{bucket="3_10"} 3121
telemt_desync_frames_bucket_total{bucket="gt_10"} 4030
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 27660
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27301
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 2515201
telemt_user_connections_current{user="hello"} 1138
telemt_user_octets_from_client{user="hello"} 41306490752 (38.47 GB)
telemt_user_octets_to_client{user="hello"} 879409209109 (819.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 159848.9 (44h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1959158
telemt_connections_bad_total 18927
telemt_handshake_timeouts_total 180965
telemt_upstream_connect_attempt_total 49526
telemt_upstream_connect_success_total 47184
telemt_upstream_connect_fail_total 2205
telemt_upstream_connect_attempts_per_request{bucket="1"} 49252
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11972
telemt_me_reconnect_attempts_total 42360
telemt_me_reconnect_success_total 33376
telemt_me_reader_eof_total 35839
telemt_me_idle_close_by_peer_total 35832
telemt_me_route_drop_no_conn_total 696731
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1616532
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3218
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 2174
telemt_desync_frames_bucket_total{bucket="1_2"} 889
telemt_desync_frames_bucket_total{bucket="3_10"} 1318
telemt_desync_frames_bucket_total{bucket="gt_10"} 1011
telemt_pool_swap_total 139
telemt_me_writer_removed_unexpected_total 33925
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33352
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 549
telemt_user_connections_total{user="hello"} 1621227
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 24984193805 (23.27 GB)
telemt_user_octets_to_client{user="hello"} 611445767002 (569.45 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29284.6 (8h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479696
telemt_connections_bad_total 4689
telemt_handshake_timeouts_total 4955
telemt_upstream_connect_attempt_total 6604
telemt_upstream_connect_success_total 6389
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 6604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 873
telemt_me_reconnect_attempts_total 20388
telemt_me_reconnect_success_total 4900
telemt_me_reader_eof_total 5480
telemt_me_idle_close_by_peer_total 5480
telemt_me_route_drop_no_conn_total 183967
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 448707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1329
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 523
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5424
telemt_me_refill_failed_total 482
telemt_me_writer_restored_same_endpoint_total 4896
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 448687
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 5063037260 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 141150818684 (131.46 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 80
```