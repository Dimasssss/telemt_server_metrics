# Server Metrics 2026-03-12 09:49:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 13834.0 (3h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444483
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 2685
telemt_upstream_connect_attempt_total 2732
telemt_upstream_connect_success_total 2717
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 280
telemt_me_reconnect_attempts_total 3274
telemt_me_reconnect_success_total 1982
telemt_me_reader_eof_total 2088
telemt_me_idle_close_by_peer_total 2088
telemt_me_route_drop_no_conn_total 151585
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2002
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1501
telemt_desync_frames_bucket_total{bucket="1_2"} 509
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 762
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2038
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 1969
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 429932
telemt_user_connections_current{user="hello"} 1346
telemt_user_octets_from_client{user="hello"} 6272405944 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 115784000912 (107.83 GB)
telemt_user_unique_ips_current{user="hello"} 373
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 43454.6 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266290
telemt_connections_bad_total 2976
telemt_handshake_timeouts_total 8266
telemt_upstream_connect_attempt_total 11002
telemt_upstream_connect_success_total 10996
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 11002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 659
telemt_me_reconnect_attempts_total 8672
telemt_me_reconnect_success_total 8629
telemt_me_reader_eof_total 9175
telemt_me_idle_close_by_peer_total 9175
telemt_me_route_drop_no_conn_total 77181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236756
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8696
telemt_me_writer_restored_same_endpoint_total 8620
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 237192
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 3328243999 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 90283856966 (84.08 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 43454.5 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699137
telemt_connections_bad_total 3400
telemt_handshake_timeouts_total 51464
telemt_upstream_connect_attempt_total 11047
telemt_upstream_connect_success_total 11042
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 11047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 544
telemt_me_reconnect_attempts_total 8576
telemt_me_reconnect_success_total 8503
telemt_me_reader_eof_total 8937
telemt_me_idle_close_by_peer_total 8937
telemt_me_route_drop_no_conn_total 150970
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432024
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2007
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 1407
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 702
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8508
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 8462
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 432283
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 5326004508 (4.96 GB)
telemt_user_octets_to_client{user="hello"} 144454573385 (134.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 43455.0 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347953
telemt_connections_bad_total 1833
telemt_handshake_timeouts_total 25246
telemt_upstream_connect_attempt_total 11933
telemt_upstream_connect_success_total 11885
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 11933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 816
telemt_me_reconnect_attempts_total 9732
telemt_me_reconnect_success_total 9695
telemt_me_reader_eof_total 10287
telemt_me_idle_close_by_peer_total 10287
telemt_me_route_drop_no_conn_total 119069
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293001
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 646
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 203
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9757
telemt_me_writer_restored_same_endpoint_total 9674
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 292823
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 3600234528 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 114935874060 (107.04 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 43454.8 (12h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393571
telemt_connections_bad_total 404
telemt_handshake_timeouts_total 3071
telemt_upstream_connect_attempt_total 14093
telemt_upstream_connect_success_total 13925
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 14093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 618
telemt_me_reconnect_attempts_total 13250
telemt_me_reconnect_success_total 11727
telemt_me_reader_eof_total 12212
telemt_me_idle_close_by_peer_total 12212
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 127218
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 371976
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 1574
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1063
telemt_desync_frames_bucket_total{bucket="1_2"} 462
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 560
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 11882
telemt_me_refill_failed_total 46
telemt_me_writer_restored_same_endpoint_total 11705
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 371909
telemt_user_connections_current{user="hello"} 696
telemt_user_octets_from_client{user="hello"} 4108668584 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 89404940420 (83.26 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 98
```