# Server Metrics 2026-03-11 14:41:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 87252.8 (24h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2113580
telemt_connections_bad_total 33607
telemt_handshake_timeouts_total 52174
telemt_upstream_connect_attempt_total 18417
telemt_upstream_connect_success_total 18405
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 18417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 4849
telemt_me_reconnect_attempts_total 29246
telemt_me_reconnect_success_total 14004
telemt_me_reader_eof_total 15132
telemt_me_idle_close_by_peer_total 15132
telemt_me_route_drop_no_conn_total 781037
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1932656
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10122
telemt_desync_full_logged_total 2744
telemt_desync_suppressed_total 7378
telemt_desync_frames_bucket_total{bucket="1_2"} 2516
telemt_desync_frames_bucket_total{bucket="3_10"} 3902
telemt_desync_frames_bucket_total{bucket="gt_10"} 3704
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14631
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 13998
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 1931156
telemt_user_connections_current{user="hello"} 1526
telemt_user_octets_from_client{user="hello"} 26028907700 (24.24 GB)
telemt_user_octets_to_client{user="hello"} 551668009140 (513.78 GB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 87309.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790508
telemt_connections_bad_total 13196
telemt_handshake_timeouts_total 53669
telemt_upstream_connect_attempt_total 27828
telemt_upstream_connect_success_total 24879
telemt_upstream_connect_fail_total 2949
telemt_upstream_connect_attempts_per_request{bucket="1"} 27828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11114
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2949
telemt_me_keepalive_timeout_total 2524
telemt_me_reconnect_attempts_total 19657
telemt_me_reconnect_success_total 17569
telemt_me_reader_eof_total 18606
telemt_me_idle_close_by_peer_total 18603
telemt_me_route_drop_no_conn_total 310124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670048
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2847
telemt_desync_full_logged_total 905
telemt_desync_suppressed_total 1942
telemt_desync_frames_bucket_total{bucket="1_2"} 882
telemt_desync_frames_bucket_total{bucket="3_10"} 1031
telemt_desync_frames_bucket_total{bucket="gt_10"} 934
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17828
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 17546
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 672525
telemt_user_connections_current{user="hello"} 560
telemt_user_octets_from_client{user="hello"} 7685273862 (7.16 GB)
telemt_user_octets_to_client{user="hello"} 190276453652 (177.21 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 87309.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1370343
telemt_connections_bad_total 8455
telemt_handshake_timeouts_total 122285
telemt_upstream_connect_attempt_total 23146
telemt_upstream_connect_success_total 22872
telemt_upstream_connect_fail_total 274
telemt_upstream_connect_attempts_per_request{bucket="1"} 23146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 274
telemt_me_keepalive_timeout_total 1564
telemt_me_reconnect_attempts_total 33528
telemt_me_reconnect_success_total 17416
telemt_me_reader_eof_total 18713
telemt_me_idle_close_by_peer_total 18713
telemt_me_route_drop_no_conn_total 495788
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1188669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3163
telemt_desync_full_logged_total 934
telemt_desync_suppressed_total 2229
telemt_desync_frames_bucket_total{bucket="1_2"} 772
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 1194
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 18154
telemt_me_refill_failed_total 499
telemt_me_writer_restored_same_endpoint_total 17405
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 738
telemt_user_connections_total{user="hello"} 1188438
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 14262585701 (13.28 GB)
telemt_user_octets_to_client{user="hello"} 355079133537 (330.69 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 87309.9 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 983518
telemt_connections_bad_total 77575
telemt_handshake_timeouts_total 94176
telemt_upstream_connect_attempt_total 23513
telemt_upstream_connect_success_total 23513
telemt_upstream_connect_attempts_per_request{bucket="1"} 23513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 962
telemt_me_reconnect_attempts_total 20244
telemt_me_reconnect_success_total 19171
telemt_me_reader_eof_total 20330
telemt_me_idle_close_by_peer_total 20329
telemt_me_seq_mismatch_total 17
telemt_me_route_drop_no_conn_total 319960
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 785125
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 28
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1679
telemt_desync_full_logged_total 648
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 19408
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 19143
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 784456
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 9175862552 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 229360593992 (213.61 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 87309.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1082053
telemt_connections_bad_total 6936
telemt_handshake_timeouts_total 10965
telemt_upstream_connect_attempt_total 23661
telemt_upstream_connect_success_total 23556
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 23661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1906
telemt_me_reconnect_attempts_total 23163
telemt_me_reconnect_success_total 19079
telemt_me_reader_eof_total 20110
telemt_me_idle_close_by_peer_total 20110
telemt_me_route_drop_no_conn_total 384190
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 982850
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3819
telemt_desync_full_logged_total 1400
telemt_desync_suppressed_total 2419
telemt_desync_frames_bucket_total{bucket="1_2"} 1333
telemt_desync_frames_bucket_total{bucket="3_10"} 1438
telemt_desync_frames_bucket_total{bucket="gt_10"} 1048
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19453
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 19079
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 982577
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 14169213631 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 344547750222 (320.89 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 114
```