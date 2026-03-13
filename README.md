# Server Metrics 2026-03-13 05:43:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 85474.7 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2299149
telemt_connections_bad_total 34365
telemt_handshake_timeouts_total 24213
telemt_upstream_connect_attempt_total 16794
telemt_upstream_connect_success_total 16701
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1315
telemt_me_reconnect_attempts_total 21331
telemt_me_reconnect_success_total 12463
telemt_me_reader_eof_total 13442
telemt_me_idle_close_by_peer_total 13441
telemt_me_route_drop_no_conn_total 873866
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2114630
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9388
telemt_desync_full_logged_total 2421
telemt_desync_suppressed_total 6967
telemt_desync_frames_bucket_total{bucket="1_2"} 2439
telemt_desync_frames_bucket_total{bucket="3_10"} 3436
telemt_desync_frames_bucket_total{bucket="gt_10"} 3513
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12911
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 12450
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 2113981
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 30579256764 (28.48 GB)
telemt_user_octets_to_client{user="hello"} 725911876596 (676.06 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 115095.1 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 931287
telemt_connections_bad_total 12417
telemt_handshake_timeouts_total 40484
telemt_upstream_connect_attempt_total 29074
telemt_upstream_connect_success_total 29043
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 29074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15000
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3557
telemt_me_reconnect_attempts_total 21808
telemt_me_reconnect_success_total 21691
telemt_me_reader_eof_total 23126
telemt_me_idle_close_by_peer_total 23126
telemt_me_route_drop_no_conn_total 296587
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 840028
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3370
telemt_desync_full_logged_total 1062
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 1327
telemt_desync_frames_bucket_total{bucket="3_10"} 1103
telemt_desync_frames_bucket_total{bucket="gt_10"} 940
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 21906
telemt_me_writer_restored_same_endpoint_total 21682
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 841922
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 13335601472 (12.42 GB)
telemt_user_octets_to_client{user="hello"} 320899663063 (298.86 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 115095.0 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1923842
telemt_connections_bad_total 21443
telemt_handshake_timeouts_total 126227
telemt_upstream_connect_attempt_total 26742
telemt_upstream_connect_success_total 26732
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 26742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1663
telemt_me_reconnect_attempts_total 21939
telemt_me_reconnect_success_total 20668
telemt_me_reader_eof_total 21892
telemt_me_idle_close_by_peer_total 21891
telemt_me_route_drop_no_conn_total 617132
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1515594
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5258
telemt_desync_full_logged_total 1601
telemt_desync_suppressed_total 3657
telemt_desync_frames_bucket_total{bucket="1_2"} 868
telemt_desync_frames_bucket_total{bucket="3_10"} 1903
telemt_desync_frames_bucket_total{bucket="gt_10"} 2487
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20867
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 20627
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 1515092
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 26021765708 (24.23 GB)
telemt_user_octets_to_client{user="hello"} 540586373973 (503.46 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 115095.3 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176889
telemt_connections_bad_total 13986
telemt_handshake_timeouts_total 76765
telemt_upstream_connect_attempt_total 39296
telemt_upstream_connect_success_total 37009
telemt_upstream_connect_fail_total 2150
telemt_upstream_connect_attempts_per_request{bucket="1"} 39022
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2149
telemt_me_keepalive_timeout_total 11403
telemt_me_reconnect_attempts_total 34366
telemt_me_reconnect_success_total 25432
telemt_me_reader_eof_total 27422
telemt_me_idle_close_by_peer_total 27415
telemt_me_route_drop_no_conn_total 419654
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1013274
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1982
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1330
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 25885
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 25408
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 1018408
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 15519757773 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 406069837858 (378.18 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 115095.1 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1322076
telemt_connections_bad_total 14513
telemt_handshake_timeouts_total 10798
telemt_upstream_connect_attempt_total 36313
telemt_upstream_connect_success_total 35878
telemt_upstream_connect_fail_total 435
telemt_upstream_connect_attempts_per_request{bucket="1"} 36313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17399
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 179
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 435
telemt_me_keepalive_timeout_total 1982
telemt_me_reconnect_attempts_total 43901
telemt_me_reconnect_success_total 30166
telemt_me_reader_eof_total 31694
telemt_me_idle_close_by_peer_total 31694
telemt_me_seq_mismatch_total 40
telemt_me_route_drop_no_conn_total 487881
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1222949
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 44
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4410
telemt_desync_full_logged_total 1587
telemt_desync_suppressed_total 2823
telemt_desync_frames_bucket_total{bucket="1_2"} 1341
telemt_desync_frames_bucket_total{bucket="3_10"} 1431
telemt_desync_frames_bucket_total{bucket="gt_10"} 1638
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 30930
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 30114
telemt_me_writer_restored_fallback_total 52
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 764
telemt_user_connections_total{user="hello"} 1222795
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 14765744876 (13.75 GB)
telemt_user_octets_to_client{user="hello"} 414367416364 (385.91 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 79
```