# Server Metrics 2026-03-10 22:44:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 29838.6 (8h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742463
telemt_connections_bad_total 8946
telemt_handshake_timeouts_total 8371
telemt_upstream_connect_attempt_total 6414
telemt_upstream_connect_success_total 6405
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 6414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3182
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 16478
telemt_me_reconnect_success_total 4818
telemt_me_reader_eof_total 5315
telemt_me_idle_close_by_peer_total 5315
telemt_me_route_drop_no_conn_total 309027
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 702237
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3471
telemt_desync_full_logged_total 968
telemt_desync_suppressed_total 2503
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1298
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5222
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 4812
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 702039
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 10033665268 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 212196951168 (197.62 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 29895.3 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321851
telemt_connections_bad_total 2372
telemt_handshake_timeouts_total 17582
telemt_upstream_connect_attempt_total 13114
telemt_upstream_connect_success_total 10245
telemt_upstream_connect_fail_total 2869
telemt_upstream_connect_attempts_per_request{bucket="1"} 13114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2031
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2869
telemt_me_keepalive_timeout_total 1379
telemt_me_reconnect_attempts_total 6550
telemt_me_reconnect_success_total 5744
telemt_me_reader_eof_total 6037
telemt_me_idle_close_by_peer_total 6035
telemt_me_route_drop_no_conn_total 167517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1637
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 1182
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 581
telemt_desync_frames_bucket_total{bucket="gt_10"} 558
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5833
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 5723
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 274107
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 2672769534 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 64411998204 (59.99 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 29895.1 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 532091
telemt_connections_bad_total 3456
telemt_handshake_timeouts_total 33849
telemt_upstream_connect_attempt_total 8217
telemt_upstream_connect_success_total 8095
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 8217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 16523
telemt_me_reconnect_success_total 5468
telemt_me_reader_eof_total 6016
telemt_me_idle_close_by_peer_total 6016
telemt_me_route_drop_no_conn_total 184436
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 466440
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1508
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 1082
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 5898
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 5457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 467372
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 6653400009 (6.20 GB)
telemt_user_octets_to_client{user="hello"} 148765982417 (138.55 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 29895.7 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375644
telemt_connections_bad_total 28748
telemt_handshake_timeouts_total 33730
telemt_upstream_connect_attempt_total 8285
telemt_upstream_connect_success_total 8285
telemt_upstream_connect_attempts_per_request{bucket="1"} 8285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 7756
telemt_me_reconnect_success_total 6732
telemt_me_reader_eof_total 7086
telemt_me_idle_close_by_peer_total 7086
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 119909
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 300257
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 690
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 178
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6836
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 6718
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 299932
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 4059556512 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 87338104584 (81.34 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 29895.2 (8h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396441
telemt_connections_bad_total 2734
telemt_handshake_timeouts_total 2588
telemt_upstream_connect_attempt_total 9231
telemt_upstream_connect_success_total 9193
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 9231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 198
telemt_me_reconnect_attempts_total 11363
telemt_me_reconnect_success_total 7604
telemt_me_reader_eof_total 7973
telemt_me_idle_close_by_peer_total 7973
telemt_me_route_drop_no_conn_total 138035
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368902
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2151
telemt_desync_full_logged_total 826
telemt_desync_suppressed_total 1325
telemt_desync_frames_bucket_total{bucket="1_2"} 796
telemt_desync_frames_bucket_total{bucket="3_10"} 920
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 7826
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 7604
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 368721
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 6440013628 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 138367897956 (128.87 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```