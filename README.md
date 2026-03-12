# Server Metrics 2026-03-12 09:18:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 11999.0 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378274
telemt_connections_bad_total 1331
telemt_handshake_timeouts_total 2398
telemt_upstream_connect_attempt_total 2285
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1041
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 268
telemt_me_reconnect_attempts_total 1638
telemt_me_reconnect_success_total 1627
telemt_me_reader_eof_total 1691
telemt_me_idle_close_by_peer_total 1691
telemt_me_route_drop_no_conn_total 128796
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1683
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1641
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 365647
telemt_user_connections_current{user="hello"} 1363
telemt_user_octets_from_client{user="hello"} 5703002228 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 101150039380 (94.20 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 41619.4 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243245
telemt_connections_bad_total 2934
telemt_handshake_timeouts_total 7819
telemt_upstream_connect_attempt_total 10619
telemt_upstream_connect_success_total 10613
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 10619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 653
telemt_me_reconnect_attempts_total 8378
telemt_me_reconnect_success_total 8335
telemt_me_reader_eof_total 8861
telemt_me_idle_close_by_peer_total 8861
telemt_me_route_drop_no_conn_total 69799
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 474
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8400
telemt_me_writer_restored_same_endpoint_total 8326
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 215272
telemt_user_connections_current{user="hello"} 642
telemt_user_octets_from_client{user="hello"} 3158075559 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 83204623138 (77.49 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 41619.6 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659899
telemt_connections_bad_total 3017
telemt_handshake_timeouts_total 48811
telemt_upstream_connect_attempt_total 10657
telemt_upstream_connect_success_total 10652
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 10657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 541
telemt_me_reconnect_attempts_total 8273
telemt_me_reconnect_success_total 8202
telemt_me_reader_eof_total 8621
telemt_me_idle_close_by_peer_total 8621
telemt_me_route_drop_no_conn_total 138345
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396678
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1797
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1260
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 955
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8201
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8161
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_user_connections_total{user="hello"} 396943
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 4951427116 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 133563949277 (124.39 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 41619.6 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324362
telemt_connections_bad_total 1827
telemt_handshake_timeouts_total 22986
telemt_upstream_connect_attempt_total 11408
telemt_upstream_connect_success_total 11362
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 11408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 808
telemt_me_reconnect_attempts_total 9296
telemt_me_reconnect_success_total 9262
telemt_me_reader_eof_total 9832
telemt_me_idle_close_by_peer_total 9832
telemt_me_route_drop_no_conn_total 110250
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272209
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 545
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 9322
telemt_me_writer_restored_same_endpoint_total 9241
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 272030
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 3206450996 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 99566389712 (92.73 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 41619.4 (11h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 361972
telemt_connections_bad_total 382
telemt_handshake_timeouts_total 2647
telemt_upstream_connect_attempt_total 13598
telemt_upstream_connect_success_total 13434
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 13598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 586
telemt_me_reconnect_attempts_total 12846
telemt_me_reconnect_success_total 11329
telemt_me_reader_eof_total 11809
telemt_me_idle_close_by_peer_total 11809
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 116232
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341736
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1433
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 959
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 502
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11478
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11307
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 341674
telemt_user_connections_current{user="hello"} 726
telemt_user_octets_from_client{user="hello"} 3704950528 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 82468467040 (76.80 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 98
```