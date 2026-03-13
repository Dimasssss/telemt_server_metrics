# Server Metrics 2026-03-13 14:24:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 116750.8 (32h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3568471
telemt_connections_bad_total 37400
telemt_handshake_timeouts_total 61052
telemt_upstream_connect_attempt_total 22821
telemt_upstream_connect_success_total 22693
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 22821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 2162
telemt_me_reconnect_attempts_total 26979
telemt_me_reconnect_success_total 16894
telemt_me_reader_eof_total 18160
telemt_me_idle_close_by_peer_total 18159
telemt_me_route_drop_no_conn_total 1326399
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3276705
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13496
telemt_desync_full_logged_total 3537
telemt_desync_suppressed_total 9959
telemt_desync_frames_bucket_total{bucket="1_2"} 3433
telemt_desync_frames_bucket_total{bucket="3_10"} 5108
telemt_desync_frames_bucket_total{bucket="gt_10"} 4955
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 17444
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16881
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 3276417
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 45043151804 (41.95 GB)
telemt_user_octets_to_client{user="hello"} 1039157487676 (967.79 GB)
telemt_user_unique_ips_current{user="hello"} 472
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 16414.5 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230462
telemt_connections_bad_total 13080
telemt_handshake_timeouts_total 5735
telemt_upstream_connect_attempt_total 4094
telemt_upstream_connect_success_total 4015
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 5420
telemt_me_reconnect_success_total 3132
telemt_me_reader_eof_total 3319
telemt_me_idle_close_by_peer_total 3319
telemt_me_route_drop_no_conn_total 83838
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205572
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 794
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3235
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 3125
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 205596
telemt_user_connections_current{user="hello"} 602
telemt_user_octets_from_client{user="hello"} 2148580872 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 59441778756 (55.36 GB)
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 146371.2 (40h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2668908
telemt_connections_bad_total 27310
telemt_handshake_timeouts_total 178285
telemt_upstream_connect_attempt_total 32998
telemt_upstream_connect_success_total 32988
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3239
telemt_me_reconnect_attempts_total 27915
telemt_me_reconnect_success_total 25368
telemt_me_reader_eof_total 26899
telemt_me_idle_close_by_peer_total 26898
telemt_me_route_drop_no_conn_total 897682
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2180930
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7791
telemt_desync_full_logged_total 2532
telemt_desync_suppressed_total 5259
telemt_desync_frames_bucket_total{bucket="1_2"} 1227
telemt_desync_frames_bucket_total{bucket="3_10"} 2839
telemt_desync_frames_bucket_total{bucket="gt_10"} 3725
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 25665
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 25327
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 2180313
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 36388646580 (33.89 GB)
telemt_user_octets_to_client{user="hello"} 773674355685 (720.54 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 146371.7 (40h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700615
telemt_connections_bad_total 18073
telemt_handshake_timeouts_total 123308
telemt_upstream_connect_attempt_total 46446
telemt_upstream_connect_success_total 44121
telemt_upstream_connect_fail_total 2188
telemt_upstream_connect_attempts_per_request{bucket="1"} 46172
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2187
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11845
telemt_me_reconnect_attempts_total 39955
telemt_me_reconnect_success_total 30986
telemt_me_reader_eof_total 33314
telemt_me_idle_close_by_peer_total 33307
telemt_me_route_drop_no_conn_total 607448
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1422026
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2831
telemt_desync_full_logged_total 920
telemt_desync_suppressed_total 1911
telemt_desync_frames_bucket_total{bucket="1_2"} 754
telemt_desync_frames_bucket_total{bucket="3_10"} 1179
telemt_desync_frames_bucket_total{bucket="gt_10"} 898
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 31498
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30962
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 1426743
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 22225742121 (20.70 GB)
telemt_user_octets_to_client{user="hello"} 550374864750 (512.58 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 15807.1 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249357
telemt_connections_bad_total 3887
telemt_handshake_timeouts_total 2383
telemt_upstream_connect_attempt_total 3283
telemt_upstream_connect_success_total 3174
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 3283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 10423
telemt_me_reconnect_success_total 2347
telemt_me_reader_eof_total 2627
telemt_me_idle_close_by_peer_total 2627
telemt_me_route_drop_no_conn_total 97958
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 232773
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 774
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2604
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 232755
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 2570777484 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 76109364116 (70.88 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 109
```