# Server Metrics 2026-03-15 12:48:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 52424.6 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1496989
telemt_connections_bad_total 87160
telemt_handshake_timeouts_total 13020
telemt_upstream_connect_attempt_total 10438
telemt_upstream_connect_success_total 10390
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 10438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 12624
telemt_me_reconnect_success_total 7742
telemt_me_reader_eof_total 8307
telemt_me_idle_close_by_peer_total 8307
telemt_me_route_drop_no_conn_total 503475
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1258220
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4713
telemt_desync_full_logged_total 1328
telemt_desync_suppressed_total 3385
telemt_desync_frames_bucket_total{bucket="1_2"} 1162
telemt_desync_frames_bucket_total{bucket="3_10"} 1855
telemt_desync_frames_bucket_total{bucket="gt_10"} 1696
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8013
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 7731
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 1257874
telemt_user_connections_current{user="hello"} 2346
telemt_user_octets_from_client{user="hello"} 17729818984 (16.51 GB)
telemt_user_octets_to_client{user="hello"} 502681462936 (468.16 GB)
telemt_user_unique_ips_current{user="hello"} 676
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 52425.3 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602291
telemt_connections_bad_total 30327
telemt_handshake_timeouts_total 38924
telemt_upstream_connect_attempt_total 13589
telemt_upstream_connect_success_total 13519
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 10617
telemt_me_reconnect_success_total 10539
telemt_me_reader_eof_total 11149
telemt_me_idle_close_by_peer_total 11149
telemt_me_route_drop_no_conn_total 151932
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 461259
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1803
telemt_desync_full_logged_total 630
telemt_desync_suppressed_total 1173
telemt_desync_frames_bucket_total{bucket="1_2"} 684
telemt_desync_frames_bucket_total{bucket="3_10"} 664
telemt_desync_frames_bucket_total{bucket="gt_10"} 455
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10660
telemt_me_writer_restored_same_endpoint_total 10527
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 461524
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 6530955783 (6.08 GB)
telemt_user_octets_to_client{user="hello"} 170878589192 (159.14 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 52425.3 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1211714
telemt_connections_bad_total 40104
telemt_handshake_timeouts_total 123515
telemt_upstream_connect_attempt_total 11589
telemt_upstream_connect_success_total 11533
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 11589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 10119
telemt_me_reconnect_success_total 8874
telemt_me_reader_eof_total 9412
telemt_me_idle_close_by_peer_total 9412
telemt_me_route_drop_no_conn_total 363225
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2073
telemt_desync_full_logged_total 747
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 832
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9028
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 8855
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 154
telemt_user_connections_total{user="hello"} 802946
telemt_user_connections_current{user="hello"} 1232
telemt_user_octets_from_client{user="hello"} 11827866680 (11.02 GB)
telemt_user_octets_to_client{user="hello"} 300411144444 (279.78 GB)
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 52425.2 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 603258
telemt_connections_bad_total 66861
telemt_handshake_timeouts_total 33464
telemt_upstream_connect_attempt_total 29085
telemt_upstream_connect_success_total 28681
telemt_upstream_connect_fail_total 404
telemt_upstream_connect_attempts_per_request{bucket="1"} 29085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 404
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 42566
telemt_me_reconnect_success_total 11735
telemt_me_reader_eof_total 13032
telemt_me_idle_close_by_peer_total 13032
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 165482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433572
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1144
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 12809
telemt_me_refill_failed_total 964
telemt_me_writer_restored_same_endpoint_total 11703
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1074
telemt_user_connections_total{user="hello"} 447738
telemt_user_connections_current{user="hello"} 729
telemt_user_octets_from_client{user="hello"} 8552945313 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 159526578184 (148.57 GB)
telemt_user_msgs_from_client{user="hello"} 206792
telemt_user_msgs_to_client{user="hello"} 1034342
telemt_user_unique_ips_current{user="hello"} 202
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 52426.5 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641247
telemt_connections_bad_total 7932
telemt_handshake_timeouts_total 13366
telemt_upstream_connect_attempt_total 11749
telemt_upstream_connect_success_total 11687
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 11749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 11364
telemt_me_reconnect_success_total 9039
telemt_me_reader_eof_total 9649
telemt_me_idle_close_by_peer_total 9649
telemt_me_route_drop_no_conn_total 159766
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520511
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2005
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1339
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 800
telemt_desync_frames_bucket_total{bucket="gt_10"} 627
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 9220
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9031
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 520543
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 6729437116 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 188672303904 (175.71 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 126
```