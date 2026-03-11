# Server Metrics 2026-03-11 12:23:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 78978.9 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1816776
telemt_connections_bad_total 26698
telemt_handshake_timeouts_total 46923
telemt_upstream_connect_attempt_total 16396
telemt_upstream_connect_success_total 16387
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 16396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8054
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 848
telemt_me_reconnect_attempts_total 25230
telemt_me_reconnect_success_total 12404
telemt_me_reader_eof_total 13420
telemt_me_idle_close_by_peer_total 13420
telemt_me_route_drop_no_conn_total 667326
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1655921
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8661
telemt_desync_full_logged_total 2339
telemt_desync_suppressed_total 6322
telemt_desync_frames_bucket_total{bucket="1_2"} 2150
telemt_desync_frames_bucket_total{bucket="3_10"} 3328
telemt_desync_frames_bucket_total{bucket="gt_10"} 3183
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 12938
telemt_me_refill_failed_total 398
telemt_me_writer_restored_same_endpoint_total 12398
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 1654463
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 21789818568 (20.29 GB)
telemt_user_octets_to_client{user="hello"} 469339744784 (437.11 GB)
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 79035.7 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 692553
telemt_connections_bad_total 12855
telemt_handshake_timeouts_total 49338
telemt_upstream_connect_attempt_total 25784
telemt_upstream_connect_success_total 22843
telemt_upstream_connect_fail_total 2941
telemt_upstream_connect_attempts_per_request{bucket="1"} 25784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2039
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2941
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 16800
telemt_me_reconnect_success_total 15941
telemt_me_reader_eof_total 16862
telemt_me_idle_close_by_peer_total 16859
telemt_me_route_drop_no_conn_total 273591
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581161
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2628
telemt_desync_full_logged_total 828
telemt_desync_suppressed_total 1800
telemt_desync_frames_bucket_total{bucket="1_2"} 833
telemt_desync_frames_bucket_total{bucket="3_10"} 960
telemt_desync_frames_bucket_total{bucket="gt_10"} 835
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16146
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 15918
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 583380
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 6275264194 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 166354099096 (154.93 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 79035.6 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1195626
telemt_connections_bad_total 7986
telemt_handshake_timeouts_total 112284
telemt_upstream_connect_attempt_total 21156
telemt_upstream_connect_success_total 20901
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 21156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_keepalive_timeout_total 858
telemt_me_reconnect_attempts_total 29495
telemt_me_reconnect_success_total 15864
telemt_me_reader_eof_total 17026
telemt_me_idle_close_by_peer_total 17026
telemt_me_route_drop_no_conn_total 402038
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1029163
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2774
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 1952
telemt_desync_frames_bucket_total{bucket="1_2"} 665
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 1062
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 16500
telemt_me_refill_failed_total 422
telemt_me_writer_restored_same_endpoint_total 15853
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 1029903
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 12024218357 (11.20 GB)
telemt_user_octets_to_client{user="hello"} 310060326213 (288.77 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 79036.0 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 861189
telemt_connections_bad_total 74161
telemt_handshake_timeouts_total 78403
telemt_upstream_connect_attempt_total 21489
telemt_upstream_connect_success_total 21489
telemt_upstream_connect_attempts_per_request{bucket="1"} 21489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 865
telemt_me_reconnect_attempts_total 18617
telemt_me_reconnect_success_total 17552
telemt_me_reader_eof_total 18607
telemt_me_idle_close_by_peer_total 18606
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 275677
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 684414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1453
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 890
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 526
telemt_desync_frames_bucket_total{bucket="gt_10"} 410
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17764
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 17525
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 683774
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 7735005412 (7.20 GB)
telemt_user_octets_to_client{user="hello"} 195090211084 (181.69 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 79035.7 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930236
telemt_connections_bad_total 6256
telemt_handshake_timeouts_total 8783
telemt_upstream_connect_attempt_total 21639
telemt_upstream_connect_success_total 21546
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 21639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 918
telemt_me_reconnect_attempts_total 21550
telemt_me_reconnect_success_total 17487
telemt_me_reader_eof_total 18455
telemt_me_idle_close_by_peer_total 18455
telemt_me_route_drop_no_conn_total 326744
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3463
telemt_desync_full_logged_total 1279
telemt_desync_suppressed_total 2184
telemt_desync_frames_bucket_total{bucket="1_2"} 1175
telemt_desync_frames_bucket_total{bucket="3_10"} 1347
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 17837
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 17487
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 350
telemt_user_connections_total{user="hello"} 844564
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 12484197907 (11.63 GB)
telemt_user_octets_to_client{user="hello"} 305260242446 (284.30 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 111
```