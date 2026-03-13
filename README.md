# Server Metrics 2026-03-13 14:29:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 117056.0 (32h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3583817
telemt_connections_bad_total 37400
telemt_handshake_timeouts_total 62058
telemt_upstream_connect_attempt_total 22871
telemt_upstream_connect_success_total 22743
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22871
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2162
telemt_me_reconnect_attempts_total 27010
telemt_me_reconnect_success_total 16924
telemt_me_reader_eof_total 18190
telemt_me_idle_close_by_peer_total 18189
telemt_me_route_drop_no_conn_total 1331279
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3289363
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13533
telemt_desync_full_logged_total 3548
telemt_desync_suppressed_total 9985
telemt_desync_frames_bucket_total{bucket="1_2"} 3436
telemt_desync_frames_bucket_total{bucket="3_10"} 5123
telemt_desync_frames_bucket_total{bucket="gt_10"} 4974
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17474
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16911
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 3289076
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 45124948636 (42.03 GB)
telemt_user_octets_to_client{user="hello"} 1042347518760 (970.76 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16719.8 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235465
telemt_connections_bad_total 13374
telemt_handshake_timeouts_total 5808
telemt_upstream_connect_attempt_total 4135
telemt_upstream_connect_success_total 4056
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5461
telemt_me_reconnect_success_total 3172
telemt_me_reader_eof_total 3361
telemt_me_idle_close_by_peer_total 3361
telemt_me_route_drop_no_conn_total 85505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210087
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 828
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 626
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3277
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3165
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 210111
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 2201893176 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 60555177356 (56.40 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 146676.6 (40h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2677334
telemt_connections_bad_total 27310
telemt_handshake_timeouts_total 178366
telemt_upstream_connect_attempt_total 33025
telemt_upstream_connect_success_total 33015
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 33025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15730
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3239
telemt_me_reconnect_attempts_total 27942
telemt_me_reconnect_success_total 25395
telemt_me_reader_eof_total 26926
telemt_me_idle_close_by_peer_total 26925
telemt_me_route_drop_no_conn_total 900563
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2188505
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7839
telemt_desync_full_logged_total 2551
telemt_desync_suppressed_total 5288
telemt_desync_frames_bucket_total{bucket="1_2"} 1236
telemt_desync_frames_bucket_total{bucket="3_10"} 2862
telemt_desync_frames_bucket_total{bucket="gt_10"} 3741
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 25692
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25354
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2187887
telemt_user_connections_current{user="hello"} 1015
telemt_user_octets_from_client{user="hello"} 36473752192 (33.97 GB)
telemt_user_octets_to_client{user="hello"} 775593039485 (722.33 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 146677.0 (40h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1705374
telemt_connections_bad_total 18073
telemt_handshake_timeouts_total 123471
telemt_upstream_connect_attempt_total 46479
telemt_upstream_connect_success_total 44154
telemt_upstream_connect_fail_total 2188
telemt_upstream_connect_attempts_per_request{bucket="1"} 46205
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11845
telemt_me_reconnect_attempts_total 39988
telemt_me_reconnect_success_total 31019
telemt_me_reader_eof_total 33347
telemt_me_idle_close_by_peer_total 33340
telemt_me_route_drop_no_conn_total 609344
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1426544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2855
telemt_desync_full_logged_total 926
telemt_desync_suppressed_total 1929
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 1191
telemt_desync_frames_bucket_total{bucket="gt_10"} 906
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 31531
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30995
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 1431261
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 22311282417 (20.78 GB)
telemt_user_octets_to_client{user="hello"} 551552639534 (513.67 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 16112.6 (4h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254681
telemt_connections_bad_total 3889
telemt_handshake_timeouts_total 2408
telemt_upstream_connect_attempt_total 3327
telemt_upstream_connect_success_total 3218
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 10467
telemt_me_reconnect_success_total 2390
telemt_me_reader_eof_total 2670
telemt_me_idle_close_by_peer_total 2670
telemt_me_route_drop_no_conn_total 100106
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237697
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 783
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2647
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2386
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 237679
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 2595088512 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 77050618712 (71.76 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 119
```