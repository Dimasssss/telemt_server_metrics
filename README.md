# Server Metrics 2026-03-11 10:00:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 70404.2 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1524666
telemt_connections_bad_total 23252
telemt_handshake_timeouts_total 40875
telemt_upstream_connect_attempt_total 14577
telemt_upstream_connect_success_total 14568
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 14577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 784
telemt_me_reconnect_attempts_total 22689
telemt_me_reconnect_success_total 11001
telemt_me_reader_eof_total 11917
telemt_me_idle_close_by_peer_total 11917
telemt_me_route_drop_no_conn_total 562146
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1383396
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6863
telemt_desync_full_logged_total 1900
telemt_desync_suppressed_total 4963
telemt_desync_frames_bucket_total{bucket="1_2"} 1813
telemt_desync_frames_bucket_total{bucket="3_10"} 2598
telemt_desync_frames_bucket_total{bucket="gt_10"} 2452
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 11474
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 10995
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 1381984
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 18150510404 (16.90 GB)
telemt_user_octets_to_client{user="hello"} 396290679920 (369.07 GB)
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70460.9 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 584160
telemt_connections_bad_total 10180
telemt_handshake_timeouts_total 33278
telemt_upstream_connect_attempt_total 23616
telemt_upstream_connect_success_total 20687
telemt_upstream_connect_fail_total 2929
telemt_upstream_connect_attempts_per_request{bucket="1"} 23616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2929
telemt_me_keepalive_timeout_total 2111
telemt_me_reconnect_attempts_total 15040
telemt_me_reconnect_success_total 14200
telemt_me_reader_eof_total 15044
telemt_me_idle_close_by_peer_total 15042
telemt_me_route_drop_no_conn_total 241445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 495424
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2238
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1550
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 688
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14369
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 14178
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 497661
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 4819234394 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 137958359140 (128.48 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 70460.9 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1015901
telemt_connections_bad_total 7606
telemt_handshake_timeouts_total 99149
telemt_upstream_connect_attempt_total 19046
telemt_upstream_connect_success_total 18810
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 19046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 777
telemt_me_reconnect_attempts_total 26556
telemt_me_reconnect_success_total 14188
telemt_me_reader_eof_total 15228
telemt_me_idle_close_by_peer_total 15228
telemt_me_route_drop_no_conn_total 333964
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869743
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2484
telemt_desync_full_logged_total 732
telemt_desync_suppressed_total 1752
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 907
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 14760
telemt_me_refill_failed_total 383
telemt_me_writer_restored_same_endpoint_total 14177
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 870596
telemt_user_connections_current{user="hello"} 814
telemt_user_octets_from_client{user="hello"} 10296350613 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 266872481409 (248.54 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 70461.3 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740828
telemt_connections_bad_total 66353
telemt_handshake_timeouts_total 71266
telemt_upstream_connect_attempt_total 19320
telemt_upstream_connect_success_total 19320
telemt_upstream_connect_attempts_per_request{bucket="1"} 19320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 713
telemt_me_reconnect_attempts_total 16844
telemt_me_reconnect_success_total 15789
telemt_me_reader_eof_total 16760
telemt_me_idle_close_by_peer_total 16759
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 231837
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580965
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1265
telemt_desync_full_logged_total 479
telemt_desync_suppressed_total 786
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 471
telemt_desync_frames_bucket_total{bucket="gt_10"} 362
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 15975
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 15765
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 580339
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 6721323476 (6.26 GB)
telemt_user_octets_to_client{user="hello"} 166615309120 (155.17 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70461.1 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 787797
telemt_connections_bad_total 6080
telemt_handshake_timeouts_total 7685
telemt_upstream_connect_attempt_total 19036
telemt_upstream_connect_success_total 18959
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 19036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 783
telemt_me_reconnect_attempts_total 19105
telemt_me_reconnect_success_total 15312
telemt_me_reader_eof_total 16193
telemt_me_idle_close_by_peer_total 16193
telemt_me_route_drop_no_conn_total 270625
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714676
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2992
telemt_desync_full_logged_total 1133
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 1046
telemt_desync_frames_bucket_total{bucket="3_10"} 1218
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 15624
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 15312
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 714355
telemt_user_connections_current{user="hello"} 807
telemt_user_octets_from_client{user="hello"} 11146165555 (10.38 GB)
telemt_user_octets_to_client{user="hello"} 259188931050 (241.39 GB)
telemt_user_msgs_from_client{user="hello"} 122
telemt_user_msgs_to_client{user="hello"} 215
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 165
```