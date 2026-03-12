# Server Metrics 2026-03-12 12:32:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 23624.6 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806130
telemt_connections_bad_total 1811
telemt_handshake_timeouts_total 5911
telemt_upstream_connect_attempt_total 4753
telemt_upstream_connect_success_total 4724
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 327
telemt_me_reconnect_attempts_total 7386
telemt_me_reconnect_success_total 3492
telemt_me_reader_eof_total 3749
telemt_me_idle_close_by_peer_total 3749
telemt_me_route_drop_no_conn_total 285771
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775557
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4066
telemt_desync_full_logged_total 1024
telemt_desync_suppressed_total 3042
telemt_desync_frames_bucket_total{bucket="1_2"} 1022
telemt_desync_frames_bucket_total{bucket="3_10"} 1477
telemt_desync_frames_bucket_total{bucket="gt_10"} 1567
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3649
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3479
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 775397
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 13314066308 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 217931266364 (202.96 GB)
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 53245.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408017
telemt_connections_bad_total 5033
telemt_handshake_timeouts_total 21658
telemt_upstream_connect_attempt_total 12955
telemt_upstream_connect_success_total 12948
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 12955
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1054
telemt_me_reconnect_attempts_total 10145
telemt_me_reconnect_success_total 10088
telemt_me_reader_eof_total 10725
telemt_me_idle_close_by_peer_total 10725
telemt_me_route_drop_no_conn_total 117250
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 359357
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1183
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 470
telemt_desync_frames_bucket_total{bucket="3_10"} 401
telemt_desync_frames_bucket_total{bucket="gt_10"} 312
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10180
telemt_me_writer_restored_same_endpoint_total 10079
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 359816
telemt_user_connections_current{user="hello"} 626
telemt_user_octets_from_client{user="hello"} 4829465663 (4.50 GB)
telemt_user_octets_to_client{user="hello"} 128324998554 (119.51 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 53245.2 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920672
telemt_connections_bad_total 5052
telemt_handshake_timeouts_total 69113
telemt_upstream_connect_attempt_total 13054
telemt_upstream_connect_success_total 13049
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5863
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 859
telemt_me_reconnect_attempts_total 10102
telemt_me_reconnect_success_total 10016
telemt_me_reader_eof_total 10548
telemt_me_idle_close_by_peer_total 10548
telemt_me_route_drop_no_conn_total 226175
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 630174
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2890
telemt_desync_full_logged_total 867
telemt_desync_suppressed_total 2023
telemt_desync_frames_bucket_total{bucket="1_2"} 416
telemt_desync_frames_bucket_total{bucket="3_10"} 1019
telemt_desync_frames_bucket_total{bucket="gt_10"} 1455
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 10042
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 9975
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 630406
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 8278988920 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 197575107037 (184.01 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 53245.8 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515453
telemt_connections_bad_total 7632
telemt_handshake_timeouts_total 47343
telemt_upstream_connect_attempt_total 14352
telemt_upstream_connect_success_total 14294
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1266
telemt_me_reconnect_attempts_total 12844
telemt_me_reconnect_success_total 11613
telemt_me_reader_eof_total 12319
telemt_me_idle_close_by_peer_total 12319
telemt_me_route_drop_no_conn_total 169604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 430135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 870
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 11735
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11592
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 429958
telemt_user_connections_current{user="hello"} 725
telemt_user_octets_from_client{user="hello"} 4896112712 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 166901776172 (155.44 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53245.5 (14h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580054
telemt_connections_bad_total 1699
telemt_handshake_timeouts_total 4580
telemt_upstream_connect_attempt_total 17254
telemt_upstream_connect_success_total 17045
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 17254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 966
telemt_me_reconnect_attempts_total 20621
telemt_me_reconnect_success_total 14357
telemt_me_reader_eof_total 15029
telemt_me_idle_close_by_peer_total 15029
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 194185
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542067
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2277
telemt_desync_full_logged_total 766
telemt_desync_suppressed_total 1511
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 797
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 14693
telemt_me_refill_failed_total 194
telemt_me_writer_restored_same_endpoint_total 14330
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 541981
telemt_user_connections_current{user="hello"} 851
telemt_user_octets_from_client{user="hello"} 6287223808 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 138289229512 (128.79 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 144
```