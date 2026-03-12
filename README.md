# Server Metrics 2026-03-12 12:57:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 25155.2 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 863614
telemt_connections_bad_total 4097
telemt_handshake_timeouts_total 7268
telemt_upstream_connect_attempt_total 4953
telemt_upstream_connect_success_total 4923
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 7541
telemt_me_reconnect_success_total 3644
telemt_me_reader_eof_total 3910
telemt_me_idle_close_by_peer_total 3910
telemt_me_route_drop_no_conn_total 306326
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827550
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4372
telemt_desync_full_logged_total 1108
telemt_desync_suppressed_total 3264
telemt_desync_frames_bucket_total{bucket="1_2"} 1089
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1697
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3806
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 3631
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 827377
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 13975800216 (13.02 GB)
telemt_user_octets_to_client{user="hello"} 241825139360 (225.22 GB)
telemt_user_unique_ips_current{user="hello"} 423
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54775.9 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430745
telemt_connections_bad_total 5257
telemt_handshake_timeouts_total 23466
telemt_upstream_connect_attempt_total 13273
telemt_upstream_connect_success_total 13266
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 13273
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1056
telemt_me_reconnect_attempts_total 10419
telemt_me_reconnect_success_total 10361
telemt_me_reader_eof_total 11008
telemt_me_idle_close_by_peer_total 11008
telemt_me_route_drop_no_conn_total 123189
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1273
telemt_desync_full_logged_total 411
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 435
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 10457
telemt_me_writer_restored_same_endpoint_total 10352
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 379999
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 5125893151 (4.77 GB)
telemt_user_octets_to_client{user="hello"} 135660364814 (126.34 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54775.8 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959546
telemt_connections_bad_total 5165
telemt_handshake_timeouts_total 72658
telemt_upstream_connect_attempt_total 13299
telemt_upstream_connect_success_total 13294
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 13299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 866
telemt_me_reconnect_attempts_total 10303
telemt_me_reconnect_success_total 10213
telemt_me_reader_eof_total 10756
telemt_me_idle_close_by_peer_total 10756
telemt_me_route_drop_no_conn_total 238739
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664798
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2978
telemt_desync_full_logged_total 898
telemt_desync_suppressed_total 2080
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 1060
telemt_desync_frames_bucket_total{bucket="gt_10"} 1493
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10243
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 10172
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 665023
telemt_user_connections_current{user="hello"} 970
telemt_user_octets_from_client{user="hello"} 8627052948 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 209449704325 (195.07 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54776.1 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541180
telemt_connections_bad_total 7640
telemt_handshake_timeouts_total 51008
telemt_upstream_connect_attempt_total 14693
telemt_upstream_connect_success_total 14635
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 14693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1270
telemt_me_reconnect_attempts_total 13139
telemt_me_reconnect_success_total 11907
telemt_me_reader_eof_total 12629
telemt_me_idle_close_by_peer_total 12629
telemt_me_route_drop_no_conn_total 181792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452115
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 916
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 265
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12035
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 11886
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 451627
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 5095658296 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 180177212100 (167.80 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54775.9 (15h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609125
telemt_connections_bad_total 1710
telemt_handshake_timeouts_total 4927
telemt_upstream_connect_attempt_total 17529
telemt_upstream_connect_success_total 17317
telemt_upstream_connect_fail_total 212
telemt_upstream_connect_attempts_per_request{bucket="1"} 17529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8796
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 212
telemt_me_keepalive_timeout_total 968
telemt_me_reconnect_attempts_total 21810
telemt_me_reconnect_success_total 14586
telemt_me_reader_eof_total 15297
telemt_me_idle_close_by_peer_total 15297
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 205863
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568506
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 26
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2360
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1560
telemt_desync_frames_bucket_total{bucket="1_2"} 666
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 864
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 14952
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 14559
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 366
telemt_user_connections_total{user="hello"} 568419
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 6548446292 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 146552024540 (136.49 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 126
```