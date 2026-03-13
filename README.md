# Server Metrics 2026-03-13 02:14:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 72925.4 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2070634
telemt_connections_bad_total 27238
telemt_handshake_timeouts_total 22058
telemt_upstream_connect_attempt_total 14425
telemt_upstream_connect_success_total 14342
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 14425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 1262
telemt_me_reconnect_attempts_total 19574
telemt_me_reconnect_success_total 10713
telemt_me_reader_eof_total 11573
telemt_me_idle_close_by_peer_total 11572
telemt_me_route_drop_no_conn_total 803167
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1918583
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8702
telemt_desync_full_logged_total 2266
telemt_desync_suppressed_total 6436
telemt_desync_frames_bucket_total{bucket="1_2"} 2294
telemt_desync_frames_bucket_total{bucket="3_10"} 3138
telemt_desync_frames_bucket_total{bucket="gt_10"} 3270
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11141
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 10700
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 1918041
telemt_user_connections_current{user="hello"} 591
telemt_user_octets_from_client{user="hello"} 28037035620 (26.11 GB)
telemt_user_octets_to_client{user="hello"} 668765622128 (622.84 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 102545.9 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849806
telemt_connections_bad_total 11794
telemt_handshake_timeouts_total 32230
telemt_upstream_connect_attempt_total 26080
telemt_upstream_connect_success_total 26051
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 26080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3451
telemt_me_reconnect_attempts_total 19419
telemt_me_reconnect_success_total 19312
telemt_me_reader_eof_total 20567
telemt_me_idle_close_by_peer_total 20567
telemt_me_route_drop_no_conn_total 273462
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770637
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3097
telemt_desync_full_logged_total 973
telemt_desync_suppressed_total 2124
telemt_desync_frames_bucket_total{bucket="1_2"} 1254
telemt_desync_frames_bucket_total{bucket="3_10"} 1006
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 19501
telemt_me_writer_restored_same_endpoint_total 19303
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 772540
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 12318893952 (11.47 GB)
telemt_user_octets_to_client{user="hello"} 291693890711 (271.66 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 102545.7 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1763281
telemt_connections_bad_total 9165
telemt_handshake_timeouts_total 118458
telemt_upstream_connect_attempt_total 23886
telemt_upstream_connect_success_total 23876
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 23886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1597
telemt_me_reconnect_attempts_total 19690
telemt_me_reconnect_success_total 18427
telemt_me_reader_eof_total 19511
telemt_me_idle_close_by_peer_total 19510
telemt_me_route_drop_no_conn_total 575815
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1386492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5005
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 3470
telemt_desync_frames_bucket_total{bucket="1_2"} 798
telemt_desync_frames_bucket_total{bucket="3_10"} 1812
telemt_desync_frames_bucket_total{bucket="gt_10"} 2395
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18601
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 18386
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1386088
telemt_user_connections_current{user="hello"} 281
telemt_user_octets_from_client{user="hello"} 20165116848 (18.78 GB)
telemt_user_octets_to_client{user="hello"} 500714234705 (466.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 102545.9 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1102672
telemt_connections_bad_total 13134
telemt_handshake_timeouts_total 73102
telemt_upstream_connect_attempt_total 35899
telemt_upstream_connect_success_total 33627
telemt_upstream_connect_fail_total 2135
telemt_upstream_connect_attempts_per_request{bucket="1"} 35625
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2134
telemt_me_keepalive_timeout_total 11281
telemt_me_reconnect_attempts_total 31589
telemt_me_reconnect_success_total 22667
telemt_me_reader_eof_total 24486
telemt_me_idle_close_by_peer_total 24479
telemt_me_route_drop_no_conn_total 390857
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 945334
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1896
telemt_desync_full_logged_total 629
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 523
telemt_desync_frames_bucket_total{bucket="3_10"} 743
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23096
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 22644
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 2298
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 950516
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 14514898945 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 372628522502 (347.04 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 102546.0 (28h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1217406
telemt_connections_bad_total 12602
telemt_handshake_timeouts_total 9502
telemt_upstream_connect_attempt_total 32288
telemt_upstream_connect_success_total 31894
telemt_upstream_connect_fail_total 394
telemt_upstream_connect_attempts_per_request{bucket="1"} 32288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 394
telemt_me_keepalive_timeout_total 1880
telemt_me_reconnect_attempts_total 39254
telemt_me_reconnect_success_total 26797
telemt_me_reader_eof_total 28145
telemt_me_idle_close_by_peer_total 28145
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 455500
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125352
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4188
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 2701
telemt_desync_frames_bucket_total{bucket="1_2"} 1256
telemt_desync_frames_bucket_total{bucket="3_10"} 1386
telemt_desync_frames_bucket_total{bucket="gt_10"} 1546
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 27492
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 26749
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 695
telemt_user_connections_total{user="hello"} 1125207
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 13797097028 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 388102556760 (361.45 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 42
```