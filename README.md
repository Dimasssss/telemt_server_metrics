# Server Metrics 2026-03-13 21:02:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 140623.9 (39h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4449443
telemt_connections_bad_total 37963
telemt_handshake_timeouts_total 106316
telemt_upstream_connect_attempt_total 29386
telemt_upstream_connect_success_total 29184
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 29386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12985
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 6559
telemt_me_reconnect_attempts_total 29938
telemt_me_reconnect_success_total 19820
telemt_me_reader_eof_total 21265
telemt_me_idle_close_by_peer_total 21264
telemt_me_route_drop_no_conn_total 1676600
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4075122
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16196
telemt_desync_full_logged_total 4320
telemt_desync_suppressed_total 11876
telemt_desync_frames_bucket_total{bucket="1_2"} 4042
telemt_desync_frames_bucket_total{bucket="3_10"} 6178
telemt_desync_frames_bucket_total{bucket="gt_10"} 5976
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20420
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19807
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 4077257
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 60041887356 (55.92 GB)
telemt_user_octets_to_client{user="hello"} 1287442480837 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40287.8 (11h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 560419
telemt_connections_bad_total 41413
telemt_handshake_timeouts_total 12195
telemt_upstream_connect_attempt_total 11544
telemt_upstream_connect_success_total 11322
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 11544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1892
telemt_me_reconnect_attempts_total 10698
telemt_me_reconnect_success_total 7275
telemt_me_reader_eof_total 7695
telemt_me_idle_close_by_peer_total 7694
telemt_me_route_drop_no_conn_total 206431
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 486480
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1633
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 579
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7487
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7267
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 488409
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 5250971761 (4.89 GB)
telemt_user_octets_to_client{user="hello"} 157729583084 (146.90 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 170244.5 (47h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3238606
telemt_connections_bad_total 30134
telemt_handshake_timeouts_total 217714
telemt_upstream_connect_attempt_total 37880
telemt_upstream_connect_success_total 37859
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 37880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10230
telemt_me_reconnect_attempts_total 33987
telemt_me_reconnect_success_total 29042
telemt_me_reader_eof_total 30813
telemt_me_idle_close_by_peer_total 30812
telemt_me_route_drop_no_conn_total 1109343
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2684490
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8853
telemt_desync_full_logged_total 2970
telemt_desync_suppressed_total 5883
telemt_desync_frames_bucket_total{bucket="1_2"} 1463
telemt_desync_frames_bucket_total{bucket="3_10"} 3227
telemt_desync_frames_bucket_total{bucket="gt_10"} 4163
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 29467
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29001
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 2683768
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 44108672600 (41.08 GB)
telemt_user_octets_to_client{user="hello"} 948085140973 (882.97 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 170245.0 (47h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2103720
telemt_connections_bad_total 22792
telemt_handshake_timeouts_total 203132
telemt_upstream_connect_attempt_total 52938
telemt_upstream_connect_success_total 50496
telemt_upstream_connect_fail_total 2305
telemt_upstream_connect_attempts_per_request{bucket="1"} 52664
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19992
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2304
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20219
telemt_me_reconnect_attempts_total 43989
telemt_me_reconnect_success_total 34978
telemt_me_reader_eof_total 37547
telemt_me_idle_close_by_peer_total 37540
telemt_me_route_drop_no_conn_total 742503
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1730898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3717
telemt_desync_full_logged_total 1191
telemt_desync_suppressed_total 2526
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1541
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35561
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 34954
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 1736769
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 26954623563 (25.10 GB)
telemt_user_octets_to_client{user="hello"} 651131366438 (606.41 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39680.5 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597885
telemt_connections_bad_total 5820
telemt_handshake_timeouts_total 5593
telemt_upstream_connect_attempt_total 8692
telemt_upstream_connect_success_total 8409
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 8692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 31021
telemt_me_reconnect_success_total 6401
telemt_me_reader_eof_total 7292
telemt_me_idle_close_by_peer_total 7291
telemt_me_route_drop_no_conn_total 227038
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 561309
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1483
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7228
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6397
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 827
telemt_user_connections_total{user="hello"} 561229
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 8361249776 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 178984447572 (166.69 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 66
```