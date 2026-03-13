# Server Metrics 2026-03-13 16:47:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 125333.2 (34h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3971879
telemt_connections_bad_total 37510
telemt_handshake_timeouts_total 96990
telemt_upstream_connect_attempt_total 24328
telemt_upstream_connect_success_total 24189
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 2287
telemt_me_reconnect_attempts_total 28040
telemt_me_reconnect_success_total 17942
telemt_me_reader_eof_total 19281
telemt_me_idle_close_by_peer_total 19280
telemt_me_route_drop_no_conn_total 1474331
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3629622
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14334
telemt_desync_full_logged_total 3785
telemt_desync_suppressed_total 10549
telemt_desync_frames_bucket_total{bucket="1_2"} 3579
telemt_desync_frames_bucket_total{bucket="3_10"} 5431
telemt_desync_frames_bucket_total{bucket="gt_10"} 5324
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18505
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 17929
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 563
telemt_user_connections_total{user="hello"} 3629427
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 51209666428 (47.69 GB)
telemt_user_octets_to_client{user="hello"} 1133770701560 (1.03 TB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 24997.2 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369120
telemt_connections_bad_total 26095
telemt_handshake_timeouts_total 10106
telemt_upstream_connect_attempt_total 5921
telemt_upstream_connect_success_total 5833
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 5921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2795
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 7896
telemt_me_reconnect_success_total 4542
telemt_me_reader_eof_total 4826
telemt_me_idle_close_by_peer_total 4825
telemt_me_route_drop_no_conn_total 132873
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323809
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1146
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 847
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4709
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 4535
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 323841
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 3250125280 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 93333759348 (86.92 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 154953.9 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2916345
telemt_connections_bad_total 28302
telemt_handshake_timeouts_total 195759
telemt_upstream_connect_attempt_total 34664
telemt_upstream_connect_success_total 34654
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 34664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16604
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3321
telemt_me_reconnect_attempts_total 29145
telemt_me_reconnect_success_total 26592
telemt_me_reader_eof_total 28199
telemt_me_idle_close_by_peer_total 28198
telemt_me_route_drop_no_conn_total 990108
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2402590
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8398
telemt_desync_full_logged_total 2776
telemt_desync_suppressed_total 5622
telemt_desync_frames_bucket_total{bucket="1_2"} 1354
telemt_desync_frames_bucket_total{bucket="3_10"} 3068
telemt_desync_frames_bucket_total{bucket="gt_10"} 3976
telemt_pool_swap_total 146
telemt_me_writer_removed_unexpected_total 26904
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 26551
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 2401958
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 39196779312 (36.50 GB)
telemt_user_octets_to_client{user="hello"} 836934697285 (779.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 154954.4 (43h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1879556
telemt_connections_bad_total 18169
telemt_handshake_timeouts_total 171730
telemt_upstream_connect_attempt_total 48485
telemt_upstream_connect_success_total 46149
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 48211
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2198
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11915
telemt_me_reconnect_attempts_total 41545
telemt_me_reconnect_success_total 32569
telemt_me_reader_eof_total 34982
telemt_me_idle_close_by_peer_total 34975
telemt_me_route_drop_no_conn_total 667007
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1548716
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3086
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2083
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1275
telemt_desync_frames_bucket_total{bucket="gt_10"} 966
telemt_pool_swap_total 135
telemt_me_writer_removed_unexpected_total 33106
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 32545
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 1553414
telemt_user_connections_current{user="hello"} 836
telemt_user_octets_from_client{user="hello"} 24033228737 (22.38 GB)
telemt_user_octets_to_client{user="hello"} 590311980686 (549.77 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 24389.6 (6h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 396436
telemt_connections_bad_total 4206
telemt_handshake_timeouts_total 3710
telemt_upstream_connect_attempt_total 5533
telemt_upstream_connect_success_total 5372
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 5532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 15808
telemt_me_reconnect_success_total 4111
telemt_me_reader_eof_total 4554
telemt_me_idle_close_by_peer_total 4554
telemt_me_route_drop_no_conn_total 154307
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370553
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1219
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 836
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4505
telemt_me_refill_failed_total 364
telemt_me_writer_restored_same_endpoint_total 4107
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 394
telemt_user_connections_total{user="hello"} 370528
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 4301776032 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 118280951108 (110.16 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 122
```